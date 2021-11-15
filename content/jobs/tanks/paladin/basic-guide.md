---
title: Paladin Basic Guide
card_header_image: /img/jobs/pld/pld-basic-guide-1-.jpg
authors:
  - Balance-PLD-Staff
patch: "5.5"
lastmod: 2021-10-27T08:23:35.725Z
changelog:
  - date: 2021-10-27T17:21:54.665Z
    message: Added
---
> the useless pre-Endwalker guide update by [nikroulah#1605](https://www.fflogs.com/character/na/adamantoise/nikroulah%20skysdotter)

- - -

## Skills and Abilities Overview

### Buffs

**Iron Will**
![](https://xivapi.com/i/002000/002505_hr1.png)

Toggle | 10s cooldown after toggling on. | No cooldown for toggling off.

Increases enmity generation by 10x (Enmity is also known as aggro, hate, etc.).

Keep this on in dungeons or as the main tank (in content with more than one tank).

**Fight or Flight**
![](https://xivapi.com/i/000000/000166_hr1.png)

60s cooldown.

+25% physical damage for 25 seconds.

By using Fight or Flight late into the GCD (just before the next GCD), it is possible to fit 11 physical GCDs into the buff window.

**Requiescat**
![](https://xivapi.com/i/002000/002513_hr1.png)

60s cooldown.

150-550 potency (magical) depending on current MP.

Scales linearly from 150 potency at 0 MP to 550 potency at max MP.

If used with at least 8,000 MP, provides a 12 second buff:

* +50% Magic Damage.
* Spells have no cast time (Lv. 78).
* Enables use of Confiteor, which removes the buff when used (Lv. 80).

### Single Target GCDs

**Goring Blade Combo**

|**Fast Blade >** | **Riot Blade >** | **Goring Blade**|
|-|-|-|
|![](https://xivapi.com/i/000000/000158_hr1.png) | ![](https://xivapi.com/i/000000/000156_hr1.png) | ![](https://xivapi.com/i/002000/002506_hr1.png)|

200 > 300 > 390 potency + 595 potency DoT over 21 seconds (physical damage).

The DoT portion snapshots buffs and debuffs when Goring Blade is cast.

+1000 MP from Riot Blade

**Royal Authority Combo**

|**Fast Blade >** | **Riot Blade >** | **Royal Authority**|
|-|-|-|
|![](https://xivapi.com/i/000000/000158_hr1.png) | ![](https://xivapi.com/i/000000/000156_hr1.png) | ![](https://xivapi.com/i/002000/002507_hr1.png)|

200 > 300 > 550 potency (physical damage)

+3 Sword Oath

+1000 MP from Riot Blade

(Upgrades from Rage of Halone).

**Atonement**
![](https://xivapi.com/i/002000/002519_hr1.png)

550 potency (physical)

Costs one Sword Oath.

+400 MP

**Holy Spirit**
![](https://xivapi.com/i/002000/002514_hr1.png)

350 potency (magical) | 1.5s cast time

Costs 2000 MP.

**Confiteor**
![](https://xivapi.com/i/002000/002518_hr1.png)

800 potency (magical damage).

Costs 2,000 MP.

AoE around target.

Requires and consumes the Requiescat buff.

### Offensive Abilities (oGCDs)

**Spirits Within**
![](https://xivapi.com/i/002000/002503_hr1.png)

100-370 potency depending on current HP (physical damage). | 30s cooldown.

Scales linearly from 100 potency at 1 HP to 370 potency at max HP.

+500 MP

**Circle of Scorn**
![](https://xivapi.com/i/000000/000161_hr1.png)

120 potency + 175 potency DoT over 15 seconds (physical damage). | 25s cooldown.

AoE centered on self.

**Intervene**
![](https://xivapi.com/i/002000/002520_hr1.png)

200 potency (physical damage). | 2 charges.

30s charge time.

### Defensive and Utility Abilities

**Rampart**
![](https://xivapi.com/i/000000/000801_hr1.png)

20% damage reduction.

20s duration | 90s cooldown

**Sentinel**
![](https://xivapi.com/i/000000/000151_hr1.png)

30% damage reduction.

15s duration | 120s cooldown

**Sheltron**
![](https://xivapi.com/i/002000/002510_hr1.png)

Guarantees blocks.

20% damage reduction (at Lv. 80).

6s duration | 6s cooldown

Costs 50 Oath Gauge, which is generated at a rate of 50 per ~23s.

**Passage of Arms**
![](https://xivapi.com/i/002000/002515_hr1.png)

Channel for up to 18 seconds.

Guarantees blocks.

120s cooldown

Provides 15% damage reduction to party members behind you (lasts at least 5s, [see FAQ](/jobs/tanks/paladin/faq/) for more details).

Cancelled by taking any action (including turning your character).

**Divine Veil**
![](https://xivapi.com/i/002000/002508_hr1.png)

If you receive a GCD heal from anybody in the next 30s, party members near you get a shield for 10% of your HP

Shield duration: 30s | 90s cooldown

**Reprisal**
![](https://xivapi.com/i/000000/000806_hr1.png)

10% damage down to nearby enemies

10s duration | 60s cooldown

**Intervention**
![](https://xivapi.com/i/002000/002512_hr1.png)

10% damage reduction

6s duration | 10s cooldown

If either Rampart or Sentinel are active on you *when you cast Intervention*, damage reduction is increased to 20% or 25% respectively, or 35% if both are active.

**Cover**<br>![](https://xivapi.com/i/002000/002501_hr1.png)

Tether to target party member as long as they are within 10y

12s duration | 120s cooldown

Redirect most damage and knockbacks on the covered target to you (exceptions exist)

Uses your buffs/debuffs (except Hallowed Ground) to calculate damage and ignores the covered target's

**Provoke**
![](https://xivapi.com/i/000000/000803_hr1.png)

Instantly gives you top enmity on the target with a significant enmity lead (this enmity lead is affected by Iron Will)

**Shirk**
![](https://xivapi.com/i/000000/000810_hr1.png)

120s cooldown

Takes 25% of your enmity and gives it to target party member.

Affects everything on the enemy list.

**Arm's Length**
![](https://xivapi.com/i/000000/000822_hr1.png)

6s duration | 120s cooldown

Become immune to most knockback and pull in effects.

Applies a 20% auto-attack and cast time slow for 15s to enemies that attack you (resisted by most bosses).

### AoE GCDs

**Prominence Combo**

|**Total Eclipse >** | **Prominence**|
|-|-|
|![](https://xivapi.com/i/002000/002511_hr1.png) | ![](https://xivapi.com/i/002000/002516_hr1.png)|

120 > 220 potency (physical damage).

+500 MP

Circle AoE centered on self.

Replaces single target combos at 3+ enemies.

**Holy Circle**
![](https://xivapi.com/i/002000/002517_hr1.png)

250 potency (magical damage)

Circle AoE centered on self.

Replaces Holy Spirit at 3+ enemies.

## Other Actions (Infrequently Used)

### GCDs

**Clemency**
![](https://xivapi.com/i/002000/002509_hr1.png)

1200 potency heal on target.

2000 MP (4,000 before Lv. 64)

When used on another target, also heals you for half as much.

**Shield Lob**
![](https://xivapi.com/i/000000/000164_hr1.png)

120 potency (physical damage)

* Enmity multiplier 
* Ranged attack

**Shield Bash**
![](https://xivapi.com/i/000000/000154_hr1.png)

110 potency (physical damage)

6s stun

### oGCDs

**Low Blow**
![](https://xivapi.com/i/000000/000802_hr1.png)

25s cooldown | 5s stun

**Interject**
![](https://xivapi.com/i/000000/000808_hr1.png)

30s cooldown

Interrupts target's action.

Interruptible actions are denoted by red flashing castbars:

Normal castbar:
![](https://xiv.sleepyshiba.com/pld/assets/cast-normal.png)

Interruptible castbar:
![](https://xiv.sleepyshiba.com/pld/assets/cast-interrupt.gif)

- - -

## Opener

Goals for PLD openers include:

* Apply Goring Blade early.
* Get important abilities like Fight or Flight and Requiescat on cooldown early.
* Use damaging oGCDs inside raid buff and potion windows (which typically come up around the 4th or 5th GCD).

![](https://xiv.sleepyshiba.com/pld/assets/rotation-opener.png)

> Text version: -2s prepull Holy Spirit > Fast Blade + Circle of Scorn + Fight or Flight > Riot Blade > Goring Blade > Fast Blade > Strength Tincture (halfway through GCD) > Riot Blade + Spirits Within + Intervene > Royal Authority + Intervene > Atonement > Atonement > Atonement > Fast Blade > Riot Blade + Circle of Scorn > Goring Blade + Requiescat > Holy Spirit > Holy Spirit > Holy Spirit > Holy Spirit > Confiteor + Spirits Within

![](https://xivapi.com/i/020000/020710_hr1.png)<br> 
The potion used is whatever the current tier's Strength potion is (as of the time of writing, and until Endwalker release, it is the Grade 4 Tincture of Strength HQ).

**High Latency Adjustments:**\
At high latency (>100ms), it can be be beneficial to move around oGCDs (not Fight or Flight or Requiescat) in order to avoid any clipping (delaying your next GCD) caused by double weaving. Additionally, move the tincture to before the first Goring Blade.

**Opener notes:**  

* We pull with a precast Holy Spirit as a medium-potency GCD that only costs half a GCD (due to precasting). Pulling with Shield Lob would be less potency and starts the GCD rolling later while pulling with Intervene moves an Intervene out of Fight or Flight.
* Circle of Scorn is used immediately (before Fight or Flight) in the opener for two reasons:

  * Its cooldown is equal to the duration of Fight or Flight, meaning that there will always be one CoS usage during FoF; the specific timing within the FoF duration is not important.
  * With a high DoT uptime, it is highly likely that any delays to CoS will result in a potency loss via lost DoT ticks by the end of the fight or phase.

- - -

## Rotation

Goals for the basic rotation are to:

* Maximize potency in personal buff windows (Fight or Flight and Requiescat).
* Keep uptime on Goring Blade (apply Goring Blade every eight or nine GCDs).
* Keep FoF and Req on cooldown as much as possible.
* Use all stacks of Sword Oath generated by using three Atonements per Royal combo.

### The Loop

The basic rotation can be thought of as *a loop starting after the previous cast of Confiteor*, and consists of an unbuffed section, a Fight or Flight window, and a Requiescat window.

Damaging oGCDs should be used on cooldown, with two charges of Intervene being pooled for Fight or Flight windows.

![](https://xiv.sleepyshiba.com/pld/assets/rotation-loop.png)

> Text Version: Loop start > Fast Blade > Riot Blade > Goring Blade > Fast Blade > Riot Blade > Royal Authority > Atonement > Atonement > Atonement > Fast Blade + Fight or Flight > Riot Blade > Goring Blade > Fast Blade > Riot Blade > Royal Authority > Atonement > Atonement > Atonement > Fast Blade > Riot Blade > Goring Blade + Requiescat > Holy Spirit > Holy Spirit > Holy Spirit > Holy Spirit > Confiteor > Loop end

### Using Fight or Flight

![](https://xiv.sleepyshiba.com/pld/assets/fofgcd.png)

Fight or Flight should be weaved approximately two-thirds of the way into the GCD roll in order to cover 11 physical GCDs, which will typically be a Royal Authority combo, 3 Atonements, a Goring Blade combo, and an extra Riot Blade and Goring Blade.

![](https://xiv.sleepyshiba.com/pld/assets/usingfof.png)

Each Fight or Flight should also ideally have 1 Circle of Scorn, 1 Spirits Within, and 2 Intervenes.

### 63 second rotation vs. 60 second rotation

At typical skill speed levels, using all available MP in Requiescat and all Sword Oath generated causes the rotation loop to be approximately 63 seconds long. This means that both Fight or Flight and Requiescat will be off cooldown for approximately 1 GCD before they are used again.

It is possible to drop a Holy Spirit from the loop (such that each Requiescat consists of 3 Holy Spirits and a Confiteor) so that personal buffs can be kept on cooldown and so that Spirits Within and Intervene don't have to be held into a slowly drifting Fight or Flight window.

Without a known phase length or kill time, the 63 second and 60 second rotations are about equal, so it is fine to default to either.

#### Why is Circle of Scorn used immediately in the opener?

Circle of Scorn is used before Fight or Flight in most openers and kept on cooldown in most phases for two reasons:

1. Its short cooldown (25 seconds) is equal to the duration of Fight or Flight, meaning one CoS usage should always occur during FoF regardless of their respective timings, given full uptime.
2. Its high DoT uptime (~60%) means that any delays are likely to cost ticks at the end of the phase, resulting in a potency loss overall.

Circle of Scorn should only be delayed in an optimized setting to line up with buffs and/or for an extra usage in tinctures *if it is guaranteed to not lose ticks*.

#### Can I use Fight or Flight after Riot Blade to make it easier to fit both Goring Blades?

Fitting both Goring Blades into each standard FoF window is a high priority, but sacrificing a buffed GCD on a regular basis to make this easier is not a good practice outside of progression, and is only necessary if encounter mechanics force a major disengagement during Fight or Flight. 10 GCD FoF windows are weaker and also limit the optimizations you can do with your rotation, such as fitting 4 Atonements into FoF.

Instead, ensure your FoF timing is precise (always in the second half of the GCD cycle, *not immediately after the previous GCD*) and you aren't double-weaving during FoF with high latency (>100 ms). As long as you keep the GCD rolling, fitting 11 GCDs into FoF with proper timing is always possible at recommended skill speeds, regardless of latency.

#### Should I save oGCDs for Fight or Flight?

Following a standard opener, every physical oGCD will naturally line up with Fight or Flight if kept on cooldown (but Intervene should usually be stacked and used twice in each FoF window). If downtime misaligns an oGCD with FoF, consider whether delaying the oGCD will cost a usage before the end of the phase. Maximizing oGCD usages is *almost always more important than fitting them into buffs*.

Use Intervene outside of FoF only if needed to keep your GCD rolling.

For optimization, line up Circle of Scorn with multi-target opportunities whenever possible, use Spirits Within earlier in the opener if necessary to avoid lining it up with incoming burst damage, and prioritize keeping uptime with Intervene during movement-heavy mechanics.

#### Should I keep Goring Blade up at all times?

Goring Blade should be applied every 8 or 9 GCDs in a full-uptime situation to maximize the potency of each usage. However, if downtime will occur immediately after Royal Authority (and cause Atonement usages to be lost), it is usually preferable to skip the previous Goring Blade and use Royal Authority earlier instead, because 3 Atonements are worth more than a Goring Blade combo.

Whenever downtime is involved, case-by-case adjustments to the rotation are recommended to avoid using inefficient Goring Blade combos which would prevent the use of Atonement (if Royal Authority must also be used) or Holy Spirit (if Requiescat is available).

### Adjustments and Recovery

Paladin's rotation is deceptively easy to recover. As a general rule, the rotation can be fully reset by each Requiescat window as long as Fight or Flight and Requiescat don't drift apart (even if they must be used sub-optimally). Losses cannot be reversed, but *ensuring personal buff windows do not desync from each other* will prevent problems from compounding for the rest of the encounter.

![](https://xiv.sleepyshiba.com/pld/assets/skill-atonement-no.png)\
For unexpected single-GCD losses, the solution is simple: drop an Atonement so FoF and Requiescat don't get delayed. If the loss occurs during the FoF window, dropping an Atonement will also ensure that the next Goring Blade is still buffed by FoF. The leftover Atonement should then replace a Holy Spirit during the Requiescat window, if possible, due to its higher potency and shorter recast time.

![](https://xiv.sleepyshiba.com/pld/assets/rotation-adjustment1.png)

![](https://xiv.sleepyshiba.com/pld/assets/skill-goringblade-no.png)\
For multiple-GCD losses (broken combos or long disengagements), the solution is to drop a Goring Blade combo at some point before the next Requiescat, because 3 Atonement/Holy Spirit usages are worth more than a full Goring Blade combo, if three GCDs must be sacrificed to prevent buff delays. Alternatively, dropping multiple Atonements (or forcing multiple Atonements into Requiescat) with standard Goring Blade timing still works, but is less efficient.

![](https://xiv.sleepyshiba.com/pld/assets/rotation-adjustment2.png)

- - -

### Helpful Macros

Co-tank macros assume your co-tank is in party slot two (default party sorting)

#### Intervention on Co-tank

```
/merror off
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/ac Intervention <2>
/micon Intervention
```


#### Mouseover Cover

```
/merror off
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/ac Cover <mo>
/micon Cover
```


#### Shirk on Co-Tank

```
/merror off
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/micon Shirk
```

**Why are there so many repeated lines?**\
FFXIV macros do not queue, so hitting a macro while in animation lock from another action will cause the macro to not go off. Since macros execute lines sequentially at around one line per frame, repeating the /action lines simulates mashing the ability every frame for ~15 frames and gives the macro a semblance of queuing.

**Mouseover? `<2>`?**\
`<mo>` will attempt to target whatever your mouse cursor is currently hovering over when that macro line is reached, whether it be their physical model or a name on your party list.

`<2>` targets the second player on your party list, which is the other tank by default in 8-man content.

- - -

## Stats and Itemization

Before obtaining best-in-slot gear, pick gear and meld according to stat priority on each piece of gear. Best-in-slot sets can be found [in the Balance Discord](https://discord.com/channels/277897135515762698/580300460179718146/847963997952016394) or [the Best in Slot page on this website](/jobs/tanks/paladin/best-in-slot/).

Because of stat tiering, the [Tank Gear Calculator](https://bit.ly/TankDPSCalc520) gets the last word on any specific gearing questions.

**Highest Priority**

**Weapon Damage** (main-hand weapon only)

* Significantly affects all damage dealt.
* Proportional to item level.

**Strength**

* Affects all damage dealt.
* Proportional to item level.

**Critical Hit**

* Affects critical chance and critical damage.
* Often naturally capped on BiS gear pieces.
* Priority meld on all gear (unless that gear piece would overcap, i.e. the number turns red when melding).

**Skill Speed**

* Reduces weaponskill recast time.
* Meld only to reach preferred GCD speed (commonly anywhere from 2.40-2.43s).
* See [precise skill speed tiers](https://www.akhmorning.com/allagan-studies/stats/speed/), courtesy of the folks over at Allagan Studies.

**Direct Hit**

* Affects only direct hit chance.
* Meld remaining slots (filler stat).

**Determination**

* Increases damage dealt and healing done.
* Sometimes used in one slot due to stat tiering.

**Tenacity**

* Increases damage dealt, healing done, and reduces damage taken.
* Rarely melded due to weak scaling and minimal impact of mitigation.

**Lowest Priority**

### Choosing your skill speed

The Paladin rotation is functional at almost all skill speeds. The only requirement is a minimum level of skill speed in order to get 11 GCDs in Fight or Flight, which is possible at virtually any recast speed faster than 2.50 (more reasonably, anything less than 2.47). In optimization, common GCD speeds have been anywhere from 2.40-2.43 this tier.

Outside of high-end optimization, choice of skill speed has little impact on the Paladin rotation, and can be chosen for comfort (faster speeds are more forgiving and latency-friendly for fitting 11 GCDs into FoF).

In optimization, each encounter must be considered separately to determine how many GCDs are gained or lost by different skill speeds, as well as lining up the GCD with any melee disengages. In general, the slowest speed that doesn't lose any major GCDs within a phase will be the strongest choice.

- - -

### Dungeons and Leveling

**Keeping Aggro**\
Turn on Iron Will and never turn it off. As long as you keep hitting the mobs, you will have aggro on them. In multi-target situations, use AoE so that you can keep aggro on all mobs.

**Pulling Mobs**\
There are a variety of ways to ensure you pull all of the mobs in a pack quickly and reliably, without stopping on your way to the next pack of mobs:

* Run up to the mobs so they see and run to you and hit an AoE combo GCD once they are in range to secure aggro.
* Tab through the mobs and use Shield Lob while weaving any damaging oGCDs or Provoke.

Try to position the mobs so that they are in a tight clump: this lets you, your dps, and your healers use their AoE damage more effectively. Pull melee enemies onto ranged enemies so that the ranged enemies are also in the clump. Alternatively, drag mobs around a corner so the ranged enemies are forced to run next to you in order to attack.

**Mitigation**\
Cycle through your mitigation on trash pulls (they hurt more than bosses). Rather than using all your mitigation at once, keeping something up at all times can help your healer keep you alive more easily. More powerful mitigation cooldowns like Rampart, Sentinel, and Arm's Length can be paired with weaker ones like Reprisal or Sheltron.

Hallowed Ground is your most powerful dungeon cooldown and should be used proactively where you expect to be taking the most damage, rather than saving it for emergencies. Aim to get at least 2 uses of Hallowed Ground in a single dungeon.

**Rotation**\
With Holy Circle unlocked, open trash pulls with Requiescat into Holy Circles + Confiteor, then spam Prominence combo under Fight or Flight and until the next Requiescat. On bosses, follow a normal single target rotation.

*Before Lv. 78:*\
Weave Requiescat late into the GCD to ensure it catches the end of your 5th Holy Spirit or Holy Circle, due to the cast time.

*Before Atonement is unlocked:*\
Replace Atonements in the single target loop with a Royal Authority combo.

*Once Goring Blade is unlocked but before Royal Authority is unlocked:*\
Since the base potency of Goring Blade is higher than that of Rage of Halone, Rage of Halone is not used until Royal Authority is unlocked (one Rage of Halone combo can be optionally used after Fight or Flight to avoid overwriting a buffed DoT with an unbuffed one for a minimal potency gain).

- - -

## Frequently Asked Questions

View more FAQs [on this page](/jobs/tanks/paladin/faq/).

### How do Cover, Divine Veil, and Passage of Arms work?

![](https://xivapi.com/i/002000/002501_hr1.png)\
Covered damage calculations ignore the target completely, and are instead based on your own stats, shields, buffs, debuffs, and cooldowns as if you were the original target, with the exception of Hallowed Ground; Hallowed Ground has no effect on covered damage, but you are still immune to personal damage received by regular means while Hallowed Ground is active.

Any debuffs or knockbacks that would have been inflicted on the covered target are often applied on you instead (if the attack hits the entire raid, whether you get two debuffs/knockbacks or one overwrites the other is entirely up to the mercy of the devs). Some things go through cover, and there is no hard and fast rule to determine what goes through cover. As a general rule, enrage-type damage will go through Cover.

![](https://xivapi.com/i/002000/002508_hr1.png)\
Upon using Divine Veil, you get a buff that has no effect unless you receive a GCD heal within the next 30 seconds. All healing spells with an on-hit potency and fairy Embrace will proc Divine Veil, but oGCD healing abilities will not.

Upon receiving a GCD heal, the initial buff on you is removed and all other party members within a 15y radius get a shield equal to 10% of your maximum HP for 30 seconds. This shield stacks with all other shields and will not be removed by additional healing, despite the misleading tooltip.

Divine Veil does not affect the Paladin directly in any way.

![](https://xivapi.com/i/002000/002515_hr1.png)\
Upon using Passage of Arms, you get a buff that blocks all incoming attacks (similar to Sheltron). This buff ends instantly when you stop channeling the ability. Attacking, moving, or using another ability will interrupt the channel. Most of the time, this part of the ability can be ignored; there is little reason to use Passage instead of Sheltron, and can require tricky timing to cover the desired damage while maintaining GCD uptime.

All other party members in an 8y cone behind you get a buff that reduces their damage taken by 15% for 5 seconds. This buff is applied even if the ability isn't channeled, but its hidden 5 second duration is refreshed whenever the server regen tick occurs while channeling (every three seconds on an independent background timer).

Passage of Arms can be channeled for up to 18 seconds if necessary, granting 20 to 23 seconds of party mitigation, depending on the alignment of the regen tick timer.

Passage of Arms snapshots your position and facing when its effects are applied, regardless of the client animation, which can make it appear to miss the party if you are moving or turning upon use (buffs will be displayed correctly on affected party members).