---
tags:
  - Mechanics/Combat
---
Blood represents your character’s core health and vitality — the life force that keeps them conscious and functioning. It is the pool of hit points that determines how injured your character can sustain before falling unconscious or dying.

**Calculation:**  
Blood = Base Blood + Vitality Attribute Score + Class Bonus + Essence Bonuses
- **Base Blood:** A starting value determined by Race's biology.
- **Vitality Score:** Your full Vitality score is added once, representing physical robustness and endurance.
- **Class Bonus** – Certain classes provide a small additional Blood pool to reflect inherent toughness.
- **Essence Bonus** – Rare, limited Essences can grant small permanent increases to Blood, representing permanent augmentation of life force.
### Damage Resolution
- When damage exceeds Sturdiness, the excess reduces **Blood**.
- If Blood reaches zero, the character falls unconscious. Each Round spent unconscious increases Exhaustion by 1 level.
- If damage drops Blood below zero, the negative amount converts into exhaustion levels, then Blood resets to zero.
    - Example: Blood = 10, Sturdiness = 3, Incoming Damage = 12 → 3 absorbed by Sturdiness, remaining 9 reduces Blood to 0 → 2 excess converts into 2 Exhaustion levels.
### Blood Thresholds and Penalties
Even when not fully depleted, low Blood imposes penalties reflecting the strain on the body. Closed wounds may reopen at dangerously low Blood levels.

| **Current Blood** | **Effect**                                                                                                                                                                     |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **>9**            | No penalty. Blood is high enough that the character functions normally.                                                                                                        |
| **9**             | Slight penalties: Gain the Breathless. Closed wounds have a 10% chance to reopen.                                                     |
| **6**             | Moderate penalties: Gain the Dazed and Disoriented. Evasion –2. Closed wounds have a 25% chance to reopen. |
| **3**             | Severe penalties: –3 to all physical Tests. Evasion –3. Closed wounds have a 50% chance to reopen.                                   |
| **0 or below**    | All closed wounds reopen.                                                                                                                                        |


> **Note:** These thresholds apply **regardless of maximum Blood**. A character with higher maximum Blood is not penalised more heavily than one with lower maximum Blood at the same absolute Blood value.

### Special Cases
- Some rare Attacks or effects bypass Sturdiness entirely, directly reducing Blood to represent grievous wounds or powerful strikes
- Essences may permanently increase Blood by a small amount, reflecting enhanced life force or monstrous traits.
- Healing mechanics, Rest, or magical effects can restore Blood over time.
