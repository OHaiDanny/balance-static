---
title: FAQ
patch: "5.58"
lastmod: 2021-10-26T23:57:40.100Z
changelog:
  - date: 2021-10-26T23:57:58.555Z
    message: "Article Created. "
qna:
  - question: How can I see my fairy's nameplate in battle?
    answer: >-
      A. Character Configuration > Control Settings > "Target" tab > Under
      "Target Settings", Uncheck "Disable targeting of pets and minions when in
      battle."


      B. Character Config > Display Name Settings > "Own" tab > Under "Pets" set "Display Name Settings" to "Always" or "During Battle"


      Both options must be set this way or your fairy's nameplate will be hidden.


      ![](https://cdn.discordapp.com/attachments/277965183366987776/594595999935234068/unknown.png)
  - question: Recitation Succor or Reci Spreadlo?
    answer: >-
      Note: Exact potencies when using Recitation are based on your own crit
      stat. Assume M is your own crit multiplier and plug it in if you want more
      precise numbers for your own gear. Every potency in the FAQ will include
      an M multiplier so the exact stat doesn't affect the comparison.


      In AoE healing situations, Recitation Succor provides a 180(M) potency heal and 225(M) potency shield (405(M) total potency) to each party member. In contrast, Recitation Spreadlo provides a 375(M) potency shield to each party member and a 300(M) potency heal and 750(M) potency shield (1050(M) total potency) to your primary target.


      As you can see, Recitation Succor provides more total potency to all party members but the primary target, assuming the heal is not wasted. Beyond this, Recitation Succor requires only an oGCD (Reci) followed by a GCD (Succ), while Reci Spreadlo requires an oGCD (Reci) followed by a GCD (Adlo) followed by another oGCD (Deploy). The biggest advantage of Reci Spreadlo is that it puts all of its potency (excluding the heal on the primary target) into shield, meaning you can go into a mechanic with more effective max HP, or use it in times when Succor would overheal such as during downtime.


      **Remember that using Recitation on uptime GCDs is generally going to be suboptimal. It's main usage will come during prog to conserve mana and give larger safety shields, but this is still very situational.**
  - question: I need oGCD help!
    answer: "![](https://cdn.discordapp.com/attachments/756684559831269426/84674616\
      7320379422/Scholar__oGCDs_8.png)"
  - question: What's the deal with Piety?
    answer: >-
      Piety is simultaneously the best and worst substat for us. It's the best
      if it allows you continue casting when you otherwise could not, otherwise
      it provides us absolutely zero gain. To lower your Piety needs do your
      best to follow these rules:


      1. Make good usage of both your own and your co-healer's oGCDs (as well as Lilies for WHM). All of these cost zero MP to use (WHM Assize actually generates MP) though it is important to remember that burning an AF stack is a 500MP opportunity cost since you're giving up a potential Energy Drain, but that's still far better than spending 1000MP on Succor or Adlo.

      2. Use Aetherflow and Lucid Dreaming on cooldown to maximize MP generation (in top end optimization Lucid will sometimes be held but DO NOT do this during prog). Your first AF is generally at the start of the fight and a good spot for first LD is often your first Bio refresh at 30s. Our other MP managing skills are Energy Drain and Recitation. ED gives 500MP with each usage so be sure not to lose AF stacks, and one use of Dissipation is generating extra stacks to dump on ED for MP. Recitation removes the AF stack cost of an AF heal (a 500MP gain) or removes the MP cost of a GCD heal (a 1000MP gain). The latter is very powerful in fights where you're forced to GCD heal and mana can get tight, but it is less DPS efficient.

      3. Carry Super-Ethers and use them when your MP is in danger (e.g. you've had to chain rez or you yourself died). This is the best way to recover your MP quickly. Remember these share CDs with damage potions so be careful about using potions if you think you will need to Ether.

      4. Coordinate with your party to use mitigation efficiently to reduce the healing load on you and your cohealer. Not having to use an AF or GCD heal to begin with is a 500/1000MP gain.


      Check out the current recommended sets for a starting amount of Piety.
  - question: Are there any macros I should know?
    answer: >-
      Macros in this game suffer from a lack of queuing like normal actions, a
      drawback shared by items (such as potions and ethers) and Sprint. For this
      reason you should never macro GCDs and should avoid using oGCD macros as
      much as possible.\

      **IMPORTANT: Add more/ac "oGCD" lines per macro to have it repeatedly execute per frame until it is on cooldown. Macros do not queue, so this gives increased reliability by allowing multiple chances for the macro to execute the ability.**


      **Valid Macro targets:**


      * `<t>`: targets your current target

      * `<tt>`: targets the target of your current target

      * `<me>`: targets yourself

      * `<f>`: targets your focus target

      * `<mo>`: targets a player/pet/enemy/etc that your mouse is over (CANNOT TARGET EMPTY GROUND)

      * `<pet>`: targets your pet

      * `<#>`: replace # with any number 1-8 to target the player in that position of your party list (`<1>` will be yourself with standard party layout)


      **Sacred Soil**\

      Sacred Soil can be slow and tricky to place as a ground effect, `<t>` and `<me>` are both useful for placing it around the boss or yourself respectively. Using `<pet>` lets you move the fairy to the required spot in advance and then place it on her.


      `/merror off`\

      `/ac "sacred soil" <t>`\

      `/ac "sacred soil" <t>`\

      `/micon "sacred soil"`


      **Place**\

      Placing the fairy does not require a weave slot so it doesn't suffer any negatives from being macroed.


      `/micon “place” pet`\

      `/pac "place" <t>`


      **Single Target Heals** Be very careful using macros for these, as they suffer from macro delay and don't have the same ground targeting issues as Sacred Soil to justify using a macro. `<mo>` and `<tt>` are generally the ones that might come in handy here.


      `/merror off`\

      `/ac excogitation <tt>`\

      `/ac excogitation <tt>`\

      `/micon excogitation`
  - question: What GCD should I have on SCH?
    answer: >-
      The short answer to this question is aim for a GCD of 2.43s or faster and
      in optimization usually 2.41s. If that's enough for you stop reading here,
      if you'd like to know more about the reasoning for this, read on.


      SCH has the most restrictive GCD requirements of the three healers when making high end sets, as running a good GCD allows for smoother Biolysis refreshes and keeping Aetherflow and Bio aligned as long as possible (as the fight allows). In an ideal world, you'd use AF under every other Bio, which saves you from weaving it with Ruin II. For general BiS sets, we generally aim for a 2.41s GCD, however there are two caveats to this:


      1. This assumes that Ruin II usage is kept to a minimum. Because Ruin II is an instant cast, it doesn't suffer from caster tax like Broil III does. This means that replacing more Broil III's with Ruin II's will shift your alignment over long periods of time, and thus 2.41s won't have a significant advantage for AF alignment. This is why we recommend GCD of 2.43s or faster rather than a hard requirement of 2.41s while gearing up. The 2.43s is enough to give you fairly clean Bio refreshes, but AF alignment over a long period of time may drift. The 2.43s is not a hard requirement though, only a recommendation. It's perfectly possible to prog at a slower GCD.

      2. 2.41s will not be the ideal GCD for every fight. Due to phase timings, other GCDs may have advantages in certain fights. A common case for this is Ultimate fights, which often have short phases where AF doesn't have enough time to drift out of Bio.
  - question: So why is SCH BiS 2.32 GCD this tier?
    answer: The short answer is that our gear absolutely sucks for 2.41s this tier.
      We either have to take on a bunch of piety or use crafted gear, and
      neither one is efficient. 2.32s GCD lines up AF well, but sits on a sort
      of halfway point of DoT timings that requires us to alternate between 12
      GCD and 13 GCD Biolysis, which can result in lost Bio ticks. This still
      makes it the most efficient GCD that we're able to hit at the moment
      damage-wise which doesn't throw off AF alignment or give us meme levels of
      mana efficiency.
  - question: Is the new relic weapon BiS?
    answer: Yes, find the sets in resources or at
      <https://dpscalc.xivresources.com/> (website is still in beta so you can't
      save your own sets at this time).
  - question: Is any of the relic armor BiS?
    answer: No, but the gloves are pretty good and let us go slower, so they're used
      in the 2.41s set.
---
# Scholar FAQ

> *How can I see my fairy's nameplate in battle?*

A. Character Configuration > Control Settings > "Target" tab > Under "Target Settings", Uncheck "Disable targeting of pets and minions when in battle."

B. Character Config > Display Name Settings > "Own" tab > Under "Pets" set "Display Name Settings" to "Always" or "During Battle"

Both options must be set this way or your fairy's nameplate will be hidden.

![](https://cdn.discordapp.com/attachments/277965183366987776/594595999935234068/unknown.png)

> *Recitation Succor or Reci Spreadlo?*  

Note: Exact potencies when using Recitation are based on your own crit stat. Assume M is your own crit multiplier and plug it in if you want more precise numbers for your own gear. Every potency in the FAQ will include an M multiplier so the exact stat doesn't affect the comparison.

In AoE healing situations, Recitation Succor provides a 180(M) potency heal and 225(M) potency shield (405(M) total potency) to each party member. In contrast, Recitation Spreadlo provides a 375(M) potency shield to each party member and a 300(M) potency heal and 750(M) potency shield (1050(M) total potency) to your primary target.

As you can see, Recitation Succor provides more total potency to all party members but the primary target, assuming the heal is not wasted. Beyond this, Recitation Succor requires only an oGCD (Reci) followed by a GCD (Succ), while Reci Spreadlo requires an oGCD (Reci) followed by a GCD (Adlo) followed by another oGCD (Deploy). The biggest advantage of Reci Spreadlo is that it puts all of its potency (excluding the heal on the primary target) into shield, meaning you can go into a mechanic with more effective max HP, or use it in times when Succor would overheal such as during downtime.

**Remember that using Recitation on uptime GCDs is generally going to be suboptimal. It's main usage will come during prog to conserve mana and give larger safety shields, but this is still very situational.**

> *I need oGCD help!*

![](https://cdn.discordapp.com/attachments/756684559831269426/846746167320379422/Scholar__oGCDs_8.png)

> *What's the deal with Piety?*

Piety is simultaneously the best and worst substat for us. It's the best if it allows you continue casting when you otherwise could not, otherwise it provides us absolutely zero gain. To lower your Piety needs do your best to follow these rules:

1. Make good usage of both your own and your cohealer's oGCDs (as well as Lilies for WHM). All of these cost zero MP to use (WHM Assize actually generates MP) though it is important to remember that burning an AF stack is a 500MP opportunity cost since you're giving up a potential Energy Drain, but that's still far better than spending 1000MP on Succor or Adlo.
2. Use Aetherflow and Lucid Dreaming on cooldown to maximize MP generation (in top end optimization Lucid will sometimes be held but DO NOT do this during prog). Your first AF is generally at the start of the fight and a good spot for first LD is often your first Bio refresh at 30s. Our other MP managing skills are Energy Drain and Recitation. ED gives 500MP with each usage so be sure not to lose AF stacks, and one use of Dissipation is generating extra stacks to dump on ED for MP. Recitation removes the AF stack cost of an AF heal (a 500MP gain) or removes the MP cost of a GCD heal (a 1000MP gain). The latter is very powerful in fights where you're forced to GCD heal and mana can get tight, but it is less DPS efficient.
3. Carry Super-Ethers and use them when your MP is in danger (e.g. you've had to chain rez or you yourself died). This is the best way to recover your MP quickly. Remember these share CDs with damage potions so be careful about using potions if you think you will need to Ether.
4. Coordinate with your party to use mitigation efficiently to reduce the healing load on you and your cohealer. Not having to use an AF or GCD heal to begin with is a 500/1000MP gain.

Checkout the current recommended sets for a starting amount of Piety.

> *Are there any macros I should know?*

Macros in this game suffer from a lack of queuing like normal actions, a drawback shared by items (such as potions and ethers) and Sprint. For this reason you should never macro GCDs and should avoid using oGCD macros as much as possible.\
**IMPORTANT: Add more/ac "oGCD" <target> lines per macro to have it repeatedly execute per frame until it is on cooldown. Macros do not queue, so this gives increased reliability by allowing multiple chances for the macro to execute the ability.**

**Valid Macro targets:**

* `<t>`: targets your current target  
* `<tt>`: targets the target of your current target  
* `<me>`: targets yourself  
* `<f>`: targets your focus target  
* `<mo>`: targets a player/pet/enemy/etc that your mouse is over (CANNOT TARGET EMPTY GROUND)
* `<pet>`: targets your pet
* `<#>`: replace # with any number 1-8 to target the player in that position of your party list (`<1>` will be yourself with standard party layout)

**Sacred Soil**\
Sacred Soil can be slow and tricky to place as a ground effect, `<t>` and `<me>` are both useful for placing it around the boss or yourself respectively. Using `<pet>` lets you move the fairy to the required spot in advance and then place it on her.

`/merror off`\
`/ac "sacred soil" <t>`\
`/ac "sacred soil" <t>`\
`/micon "sacred soil"`

**Place**\
Placing the fairy does not require a weave slot so it doesn't suffer any negatives from being macroed.

`/micon “place” pet`\
`/pac "place" <t>`

**Single Target Heals**
Be very careful using macros for these, as they suffer from macro delay and don't have the same ground targeting issues as Sacred Soil to justify using a macro. `<mo>` and `<tt>` are generally the ones that might come in handy here.

`/merror off`\
`/ac excogitation <tt>`\
`/ac excogitation <tt>`\
`/micon excogitation`

> *What GCD should I have on SCH?*

The short answer to this question is aim for a GCD of 2.43s or faster and in optimization usually 2.41s. If that's enough for you stop reading here, if you'd like to know more about the reasoning for this, read on.

SCH has the most restrictive GCD requirements of the three healers when making high end sets, as running a good GCD allows for smoother Biolysis refreshes and keeping Aetherflow and Bio aligned as long as possible (as the fight allows). In an ideal world, you'd use AF under every other Bio, which saves you from weaving it with Ruin II. For general BiS sets, we generally aim for a 2.41s GCD, however there are two caveats to this:

1. This assumes that Ruin II usage is kept to a minimum. Because Ruin II is an instant cast, it doesn't suffer from caster tax like Broil III does. This means that replacing more Broil III's with Ruin II's will shift your alignment over long periods of time, and thus 2.41s won't have a significant advantage for AF alignment. This is why we recommend GCD of 2.43s or faster rather than a hard requirement of 2.41s while gearing up. The 2.43s is enough to give you fairly clean Bio refreshes, but AF alignment over a long period of time may drift. The 2.43s is not a hard requirement though, only a recommendation. It's perfectly possible to prog at a slower GCD.
2. 2.41s will not be the ideal GCD for every fight. Due to phase timings, other GCDs may have advantages in certain fights. A common case for this is Ultimate fights, which often have short phases where AF doesn't have enough time to drift out of Bio.

> *So why the hell is SCH BiS 2.32 GCD this tier?*

The short answer is that our gear absolutely sucks for 2.41s this tier. We either have to take on a bunch of piety or use crafted gear, and neither one is efficient. 2.32s GCD lines up AF well, but sits on a sort of halfway point of DoT timings that requires us to alternate between 12 GCD and 13 GCD Bios, which can result in lost Bio ticks. This still makes it the most efficient GCD that we're able to hit at the moment damage wise, that doesn't throw off AF alignment or give us meme levels of mana efficiency.

> *Is the new relic weapon BiS?*

Yes, find the sets in resources or at <https://dpscalc.xivresources.com/> (website is still in beta so you can't save your own sets at this time).

> *Is any of the relic armor BiS?*

No, but the gloves are pretty good and let us go slower, so they're used in the 2.41s set.