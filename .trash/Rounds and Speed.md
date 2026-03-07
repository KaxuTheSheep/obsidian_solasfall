---
aliases:
  - Speed
  - Round
  - Rounds
  - Speeds
tags:
  - Mechanics/Combat
---
## Round Structure
Combat is divided into rounds, each representing a short span of time—about 5 seconds—during which all participants act simultaneously. Every round, each combatant declares their intended Actions, including Attacks, movement, Skills, or interactions.

## Action Declaration
Players discuss and coordinate their plans but do not know the exact timing of enemy Actions. After all intentions are declared, the GM orders Actions based on their assigned Speed Statistic.

## Speed Statistic
- Each action, ability, or movement has a numeric Speed Statistic.
- Higher values represent faster Actions; lower values represent slower Actions.
- Combatants’ Actions are resolved in descending order of Speed Statistic, with all Actions sharing the same value resolving simultaneously.

## Resolving Actions
- The GM resolves Actions one Speed Statistic tier at a time, narrating outcomes as they occur.
- When an action requires a roll, the relevant player or GM rolls immediately before proceeding to the next action.
- Earlier resolved Actions may impact subsequent ones (e.g., a creature killed before acting cannot perform its attack).

## Staggered Speed
Players may choose to perform Actions at a reduced Speed Statistic to better time their Attacks or Actions relative to other events. Unlike Ready Actions, which occur reactively at a lower Speed to respond to a trigger, staggered speed allows players to intentionally synchronize their Actions with allies by acting simultaneously at the same Speed Statistic. This provides tactical flexibility to coordinate efforts without sacrificing the order of resolution.

## Tie Resolution
If two or more Actions share the same Speed Statistic, the action of the combatant with the higher **Grace** Attribute resolves first.  
If Grace Attribute also tie, the GM decides the order in a manner best supporting the narrative and encounter flow.

## Reactive Abilities and Speed  
Some abilities allow a combatant to act **reactively** when triggered by an enemy’s declared action, before the triggering action is resolved. These are not declared at the start of the round and instead interrupt the sequence if their Speed is high enough.
Example - **Quick Reflexes**:
- **Trigger:** Once per combat, when an enemy targets you with an attack or effect but has not yet rolled the attack.
- **Effect:** You may immediately move up to half your Walking Distance at **Speed 14**, ignoring any Ready Actions against you.
- If your Quick Reflexes Speed is higher than the triggering action’s Speed, you move before it resolves. If lower, the enemy acts first.
Scenario:
- Player A: Declares **Run** (Speed 9) then **Attack** (Speed 7).
- Player B: Declares **Shoot** (Speed 7). Player B has **Quick Reflexes** but does **not** declare it proactively (it’s reactive).
- Monster X: Declares **Quick Strike** targeting **Player B**, Action Speed **10** (a relatively fast attack).
Resolution:
1. All intentions are revealed. Monster X has targeted Player B but has not yet rolled. That **qualifies** Player B to use Quick Reflexes.
2. Player B elects to trigger **Quick Reflexes**. The reactive move resolves at **Speed 14** — it resolves **before** Monster X’s Speed 10 attack. Player B moves half their Walk (e.g., 4.5 meters) out of the line/position. Because Player B moved before Monster X acts, Monster X’s attack now resolves against Player B’s **new** position: if out of range the attack fails; if still in range it suffers the normal movement penalty rules (–2 for ranged tracking, melee fails if out of reach).
3. Next resolve Player A’s **Run** at Speed 9, then the Speed 7 full Actions (Player A’s Attack and Player B’s Shoot), and finally Monster X’s attack if it still applies.
Contrast: if Monster X had Speed **16**, Monster X’s attack would resolve **before** Player B’s Quick Reflexes (16 > 14), so Quick Reflexes would be too late and Player B would be hit before moving.

### Action Repetition Fatigue
Repeating the **same Action** multiple times across rounds causes that Action to become slower, as technique becomes predictable and physical strain sets in.
This rule applies to:
- Weapon Attacks (each distinct attack is tracked separately)
- **Block**
- **Parry**
- Specific Spells / Techniques
It does **not** apply to:
- Movement
- Changing facing
- Speaking / Free Actions

|**Same Action Used Consecutively**|**Speed Penalty for that Action**|
|---|---|
|First use|No penalty|
|Second use|–1 Speed|
|Third use|–2 Speed|
|Fourth or more|–3 Speed (maximum penalty)|
### Resetting the Chain
If you perform a **different action**, the sequence resets at the **start of your next turn**.
**Example:**  
Round 1 → Slash (no penalty)  
Round 2 → Slash again (–1 Speed)  
Round 3 → **Block** → sequence resets next round  
Round 4 → Slash again (no penalty)
#### Defensive Actions Are Not Exempt
Repeating **Block** or **Parry** also stacks the penalty:
- Block → Block → Block becomes slower to initiate.
- Parry → Parry → Parry becomes slower to time.