<template>
  <div>
    <div class="card">
      <div class="card-header">
        Calculate your returns
      </div>
      <div class="card-body">
        <div class="row">
          <div class="col-md-6 vertical-align-center">
            <div class="input-group my-2 w-100">
              <label>Your Solana Stake
              <input type="text" class="form-control w-100" v-model="stake">
              </label>
            </div>
            <div class="input-group my-2">
              <label>Current Network APY
              <input type="number" class="form-control w-100" v-model="apy" step="0.1">
              </label>
            </div>
            <div class="input-group my-2">
              <label>Increase In Solana Price <small>({{ priceIncrease }}%)</small>
              <input type="range" class="form-control" v-model="priceIncrease" max="500">
                <div class="small text-muted">How much do you anticipate SOL to rise in a year?</div>
              </label>
            </div>
          </div>
          <div class="col text-center">
            <h2>{{ (stake * (1 + (apy/100/12))).toFixed(3)  }}
              <small class="font-weight-light small">($ {{ (stake * (1 + (apy/100/12)) * solusd * (1+priceIncrease/100)).toFixed(2)  }})</small></h2>

            <div class="text-muted text-uppercase">Assets after 1 month</div>

            <h2>{{ (stake * (1 + (apy/100)) ).toFixed(3) }}
              <small class="font-weight-light small">($ {{ (stake * (1 + (apy/100)) * solusd * (1+priceIncrease/100)).toFixed(2)  }})</small></h2>
            <div class="text-muted text-uppercase">Assets after 1 year</div>
            <h2>{{ (stake * (1 + (apy/100)) * (1 + (apy/100)) * (1 + (apy/100))  ).toFixed(3) }}
              <small class="font-weight-light small">($ {{ (stake * (1 + (apy/100))  * (1 + (apy/100)) * (1 + (apy/100)) * solusd * (1+priceIncrease/100)).toFixed(2)  }})</small></h2>
            <div class="text-muted text-uppercase">Assets after 3 years</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  module.exports = {
    name: "calculator",
    data() {
      return {
        stake: 5,
        apy: 8.2,
        priceIncrease: 0,
        gecko: {},
        solusd: 0

      }

    },
  mounted () {
  fetch('https://api.coingecko.com/api/v3/coins/solana').then(r =>  r.json()).then((data) => {
    console.log(data)
    this.gecko = data
    this.solusd = this.gecko.tickers[0].last
  })

}
}
</script>

<style scoped>

</style>
