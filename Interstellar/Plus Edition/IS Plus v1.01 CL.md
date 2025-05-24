* General:
- MaxActiveEnemies is increased 90/180/240 -> 115/225/300.
- All Extraction ECM multipliers: x1.66 -> x1.75.
- ECM multipliers change for certain mission types:
  + Egg Hunt: If the egg is not Announced Swarm, ECM: x4 -> x4.5.
  + Refinery: Refining and Refine Complete phases ECM: x1.2 -> x1.33. Refining Stalled: x0.9 -> x1
  + PE: PE Countdown, Extraction ECM: x2 -> x2.2. During Encounters and Pressure Wave (Except Announced Wave), ECM: x1.125 -> x1.2
  + Salvage: During Defend, ECM: x1.15 -> x1.25. Elapsed Extraction additive multiplier: x0.02 -> x0.022.
  + Escort: Final Event A, B, C ECM: 0.9/0.925/0.96 -> 1.
  + Sabotage: Hacking ECM: x1 -> x1.1. Before hacking/Between Hacks/Hacking Finished/Caretaker phases ECM increased to x1.
  + Deep Scan: During Drillevator, ECM: x1.2 -> x1.33. Pressure Wave (Except Encounters and Announced Swarm), ECM: x0.8/0.9 -> x0.9/1. 
- Enemy Wave Interval: 
  + Bin with 90-110s: Weight 80% -> 89%. In 1p and Deep Scan, -61% -> -60% of the weight.
  + Bin with 110-140s: Weight 19% -> 10%. In 1p and Deep Scan, +61% -> +60% of the weight.
  + Bin with 7s: 7 -> 0s. Removed restrictions on Mission Types (Apply for 1p setting too).
- Enemy Normal Wave Interval (Also applies for Dread/Caretaker Normal Wave WS):
  + Bin with 120s: Weight 65% -> 60%. In 1p and Deep Scan/Escort/Salvage/Sabotage, -45% -> -30% of the weight.
  + Bin with 150-180s: Weight 35% -> 30%. In 1p and Deep Scan/Escort/Salvage/Sabotage, +45% -> +30% of the weight.
  + Added new bin of 0s with the weight of 10%.
- Enemy Normal Wave Difficulty (Also applies for Dread/Caretaker Normal Wave WS):
  + Bin with 2000: Weight 10% -> 20%.
  + Bin with 800-900: Weight 90% -> 80%.
- Enemy Diversity:
  + Bin with 1 and Weight 15%: Removed
  + Bin with 4-7: Weight 40% -> 48%.
  + Bin with 8-11: Weight 23% -> 30%.
* Enemies:
- Cave Leech: Grabbing and Damaging speed x1.5/2 -> x1.75/2.5.
- Shocker: MaxSpawnCount 3/10 -> 5/15.
- Shredder: MaxSpawnCount 10 -> 15.
- Ice Detonator: Now carve with same Diameter as Sonic Bulk. Added back 8 Meatballs on death.
- Grunt (From Wave Spawner): MaxSpawnCount 60 -> 80. SpawnAmountModifier 0.7 -> 0.55. Difficulty Rating 10 -> 8.
- Stalker: Now uses Vanilla variant instead of Beta variant.
- Stingtail: Rarity 7.5/6.375/5.75 -> 7/6/5.25
- Ratter: Movement Speed +50% -> TimeDilation +50%.
* WaveSpawner:
- Weak Elite WaveSpawner: Pause when a downed player is detected -> Will only pause for 15s when a downed player is detected, then resume the WaveSpawner (Duration can be resetted if another player is downed during the paused duration).