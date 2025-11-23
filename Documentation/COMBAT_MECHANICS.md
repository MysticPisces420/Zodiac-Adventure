# Combat Mechanics Documentation

## Overview
This document details the combat system design for Zodiac Adventure, including the real-time hybrid combat mechanics, ability usage, damage calculation, status effects, and difficulty balancing.

## 1. Real-Time Hybrid Combat Mechanics
- **Combat Style**: Players engage in real-time combat where they can move, attack, and use abilities simultaneously.
- **Input System**: Actions are performed using combination of keyboard and mouse inputs. Players can execute light and heavy attacks, dodge, and block.
- **Target Lock Mechanic**: Players can lock onto enemies to enhance targeting accuracy.
- **Stamina System**: Each action consumes stamina; if stamina runs out, actions become slower, affecting combat performance.

## 2. Ability Usage
- **Ability Types**: Players have access to offensive, defensive, and supportive abilities.
  - **Offensive**: Inflict damage and apply status effects.
  - **Defensive**: Mitigate damage and provide temporary invulnerability.
  - **Supportive**: Heal allies or boost their abilities.
- **Usage Limitations**: Abilities have cooldowns and require resources (e.g., mana) to use.
- **Combos**: Players can chain abilities together for increased damage or unique effects.

## 3. Damage Calculation
- **Base Damage**: Each attack has a base damage value influenced by the character's stats.
- **Damage Modifiers**: 
  - **Critical Hits**: A percentage chance to deal double damage.
  - **Combo Hits**: Additive damage bonus for consecutive successful hits.
  - **Environmental Factors**: Certain areas may enhance or reduce damage dealt.
- **Damage Types**: Different damage types (e.g., physical, magical) may have strengths or weaknesses against certain enemies.

## 4. Status Effects
- **Types of Status Effects**: 
  - **Burn**: Inflicts damage over time.
  - **Freeze**: Slows down movement and attack speed.
  - **Poison**: Gradual health reduction.
  - **Blind**: Reduces accuracy.
- **Duration and Stacking**: Status effects can stack and have varying durations based on ability and enemy.

## 5. Difficulty Balancing
- **Dynamic Difficulty Adjustment**: Game adjusts enemy strength based on player performance.
- **Enemy Variety**: Different enemy types offer unique challenges and require diverse strategies.
- **Scaling Mechanics**: As the player levels up, enemies' health and damage output scale accordingly to maintain challenge.
- **Player Feedback**: Incorporate feedback from player testing to refine difficulty levels and combat mechanics.

## Conclusion
This combat mechanics design aims to create a challenging yet fun experience for players, encouraging skillful play and teamwork. Continuous iterations and testing will ensure the system remains engaging.