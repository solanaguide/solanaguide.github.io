---
seotitle: "Choosing The Best Solana Staking Validator Pool To Stake On"
title: "Find The Best Solana Validator"
description: "Our guide to choosing a validator to stake with. It's not as simple as you think!"
lead: "Are you looking to find the best validator to stake your Solana on for maximum crypto rewards?

       Wallets such as Phantom have made selecting a validation pool as simple as two clicks of your mouse. But it pays to spend a bit more time thinking about where to delegate your stake.

       While Solana's built in security means there are no worries about losing your stake by making the wrong choice, your decision can have a surprising impact on the annual returns (APY) or yield you earn from your stake and even the overall network health!"
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  docs:
    parent: "Staking"
    name: "Choosing The Best Solana Validator"
weight: 105
toc: true
---


<div class="alert alert-warning" icon="💡">
  <div class="p-3 text-center">
### Today's Recommended Validator: <a href='https://laine.co.za/solana?utm_source=solanaguide' target=_blank onclick="plausible('Validator Link')">Laine</a>

Vote account:

<div onclick="plausible('Vote Account')">

```bash
GE6atKoWiQ2pt3zL7N13pjNHjdLVys8LinG8qeJLcAiL
```

</div>

We're trying to highlight quality smaller validators where you can get good returns while helping decentralize Solana.
We like Laine, because:

- It offers 0% commission
- Consistently top APY on StakeView.app
- Proactive and resourceful operator during Solana's recent halt
</div>
</div>

---

## How to choose a platform to stake your Solana: the 3 key factors to consider

### 1.  The size of the validator's total stake (big isn't beautiful!)

The vast majority of people staking on Solana choose the 'top' validators to delegate their stake to. It's a natural choice!

By default we assume that the wisdom of crowds has chosen for us: this place is popular, it must be the best. Whether it's the way people want to eat at a busy restaurant rather than a deserted one (*who knows what their kitchen looks like?!)* or simply seeking security for their hard earned coins, choosing the well travelled path is a natural, human reaction.

The feeling is compounded by the fact that most lists of validators *sort by stake*, so the biggest in terms of scale almost always appear at the top of validator lists - including in some of the most popular Solana wallets

But while natural, these feelings are deceptive for two reasons:

1. **Your coins are safe, wherever they are staked:**
Solana's staking  system has been designed with safety in mind. Your staked funds are protected at all times, regardless of which validator you pick to generate your rewards. It doesn't matter if a validator has 10 million coins in delegated stake or just 100 - your assets are equally safe with either
2. **Solana's network relies on decentralization for Proof Of Stake to work**
The way Solana processes and approves transactions relies on stakes being spread across a wide range of validators. The more diverse and decentralized stakes are, the better for the health of the network overall.
There is a risk inherent in everyone choosing the most popular validator to stake their coins with: if the majority of coins end up staked with a small number of validators it can lead to a network halt, where inbuilt protections on the integrity of transactions stop working.
Instead, for the sake of the network, it makes sense to spread stakes out across a far greater number of validators to prevent the likelyhood of a halt or intentional attack.

If you're aiming to invest in Solana staking it is in your best interests to support the network by avoiding further concentration of stake among the biggest validators.

So our recommendation is as follows:

**Don't choose the biggest operators for the sake of their size alone.** If anything, you should actively avoid them, and either:

- Support some of the smaller operators to grow their stake and further decentralize the network
- Or spread your stake out across multiple small operators to decentralize even more

### 2. The amount of commission the validator charges

Every validator earns rewards from Solana based on the size of stake they hold. These rewards are then passed to the stake owners, minus a fee that is set by the validator itself.

Fees typically range from 0% (typically for 'startup' validators aiming to attract new stakes) to 10+% for larger validators, or those with big brand names (we're looking at you, exchanges and certain wallets!)

Working out the commission is straightforward: every validator's commission is exposed publically, and it is simply deducted as a proportion of your rewards (not your stake!)

**For example:**

You stake 100 sol at a validator with 10% commission for one year. The APY for Solana during this period is 8%.

- Your 100 SOL generates 8 SOL in rewards
- 0.8 SOL (10% of those 8 SOL )is kept as a fee by the validator
- You receive a total of 7.2 SOL over the course of the year
- At the end of the year you own 107.2 SOL

Naturally it's clear to see that the lower a commission, the greater your personal rewards. But commission is important to ensure a validator can afford to keep validating, giving them an incentive to keep their clusters performing well and generating rewards for you.

And as we'll see next, it's actually not always the biggest impact on your overall return:

> **Quick tip:** When choosing a validator ensure you know which metrics you are looking at.
For example. in Phantom Wallet (one of Solana's most popular) not only are validators listed by the biggest stake first (boo!) but they also show the commission rate next to each validator.. unlabelled.
To many first timers this can look like the APY reward you will see, not the actual commission paid! In reality the *lower* the number is in Phantom Wallet, the better for you.

### 3. The overall performance of the validator pool

Finally the last factor is crucial to the amount of rewards you receive is **the performance, reliability and stability of the validator.**

As a staker, this isn't always obvious.

But the simple fact is, if your validator's server gets disconnected from the internet, turned off or otherwise breaks then it stops competing for rewards.

If it stops participating in the Solana network, there are no rewards to pay out to stakeholders. So your APY can be affected far more dramatically by slow or broken validators than by their commission.

Similarly, rewards are also based on *the amount of work done by a validator*. This is not quite proof of work in the sense of Bitcoin, GPU farms and environmental destruction. But the fact is a validator earns rewards for every vote it participates in. If it doesn't show up - or is late - then no rewards are paid.

Solana has been built for speed, and so if the hardware a validator is using is too slow to keep up, it will simply be ignored or 'skipped'.

This can be seen by the 'Skipped Vote %' shown on [Validators.app](http://validators.app) . The less votes skipped, the higher the rewards earned each epoch. The higher the rewards, the greater your own share.

Putting all these factors together can be complex, which is why a kind soul created [stakeview.app](http://stakeview.app) , which ranks validators not by overall size, but by expected APY, taking into account validator speed as well as commission.

Exploring this site today* brings up some interesting numbers:

- Top is their own validator, with a large stake, high performance and 0% commission
- Next are some tiny validators with awesome tech. Many offer 0%, but only those that can deliver the best performance are providing returns over 8% - again proving that bigger isn't necessarily bigger
- But the most interesting part is when we get into commission rates:
    - 3 validators charging 5% commission have an estimated APY of 7.67%
    You can see here that the commission is eating into the returns compared to the 0% commission operators.. BUT
    - There is a '5% commission' validator that would only earn 4.1% .. and a number at 0% due to being completely offline

* (it's a dynamic site so specifics may change but the points remain)

So as you can see, an unreliable validator could drag your rewards down to half what you expect - or worse.

## Where to find the top validators

As you can see, there is a lot to weigh up that some lists of validators such as the frequently recommended [solanabeach.io](http://solanabeach.io) simply don't show.

For an alternative perspective we've really enjoyed looking at both [validators.app](http://validators.app) and [stakeview.app](http://stakeview.app) for both a qualitative and quantitative look at the better validators to stake with.

They take a different approach: StakeView focuses on raw returns, factoring in performance and commission rates, while Validators takes a more holistic view, looking at factors such as :

- Does it have a website?
- Do they publish a security policy?
- How well are they keeping up with other validators in terms of performance?
- Are they based in an 'over populated' datacentre where many validators are found (too much  centralization!) or out on their own in another part of the world, helping overall network reliability?
- Do they already hold too much stake?

Both tools are great resources for weighing up the pros and cons of each validator, and we recommend exploring both as you make your choice.
