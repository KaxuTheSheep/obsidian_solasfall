---
tags:
  - Mechanics/Combat
---
Blood represents your character's core health and vitality — the life force that keeps them conscious and functioning. It is the pool that determines how much injury your character can sustain before falling unconscious or dying.

## Calculation
**Blood = Base Blood + Vitality + Class Bonus + Essence Bonuses**

- **Base Blood:** A starting value determined by your Race's biology.
- **Vitality:** Your Vitality Attribute added directly, representing physical robustness and endurance.
- **Class Bonus:** Certain classes provide a small additional Blood pool to reflect inherent toughness.
- **Essence Bonus:** Rare Essences can grant small permanent increases to Blood (+1 to +2 at most), representing permanent augmentation of life force.

## Damage Resolution
- When damage exceeds Sturdiness, the excess reduces Blood.
- If Blood reaches zero, the character falls unconscious. Each Round spent unconscious increases Exhaustion by 1 level.
- If damage drops Blood below zero, the negative amount converts into Exhaustion levels, then Blood resets to zero.

> **Example:** Blood = 12, Sturdiness = 4, Incoming Damage = 14 → 4 absorbed by Sturdiness, remaining 10 reduces Blood to 2 → no excess.
> **Example:** Blood = 8, Sturdiness = 2, Incoming Damage = 12 → 2 absorbed by Sturdiness, remaining 10 reduces Blood to 0 → 2 excess converts into 2 Exhaustion levels.

## Blood Thresholds and Penalties
Even when not fully depleted, low Blood imposes penalties reflecting the strain on the body. Closed wounds may reopen at dangerously low Blood levels.

| Blood Remaining | Effect |
|-----------------|--------|
| >75%            | No penalty. The character functions normally. |
| 50–75%          | Gain **Breathless**. Closed wounds have a 5% chance to reopen. |
| 25–50%          | Gain **Dazed** and **Disoriented**. Evasion –2. Closed wounds have a 10% chance to reopen. |
| <25%            | Severe penalties: –3 to all physical Tests. Evasion –3. Closed wounds have a 25% chance to reopen. |
| 0 or below      | All closed wounds reopen. |

> Thresholds are based on your current Blood as a percentage of your maximum. A character with higher maximum Blood is not penalised more heavily than one with lower maximum Blood at the same relative point.

## Special Cases
- Some attacks or effects bypass Sturdiness entirely, directly reducing Blood to represent grievous wounds or powerful strikes.
- Essences may permanently increase Blood by a small amount, reflecting enhanced life force or monstrous traits.
- Healing, Rest, or magical effects can restore Blood over time.