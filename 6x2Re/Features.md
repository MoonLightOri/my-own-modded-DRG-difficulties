  Changelogs [v1.0]:
- MinPoolSize, DisruptiveEnemyPool, StationaryEnemyDiversity is now at maximum number. Meaning every single enemies (except biome-bound enemies cuz they are still bound to biome) can have a chance to be spawned in a mission, but they are still being restricted by EnemyDiversity values per waves/swarms.
- Swarm Interval: Min and Max value is now tighten up from 125-165 -> 135-155. In Refinery Solo, after 200s of time passed, Swarm Timer will switch to 240s interval. 
- Normal Wave Interval: In Salvage, After repair all mini-mules but before Uplink/after Uplink but before Refill, Wave Timer switches to a bin of 270s. In Refinery, after 200s of time passed, Wave Timer switches to a bin of 210s.
- Normal Wave Difficulty, Solo: In Refinery and Salvage, increase Difficulty by 20%.
- Encounters Difficulty, Solo: Reduce Difficulty by 30% on Refinery and Salvage.
- Stationary Difficulty, Solo: Reduce Difficulty by 20% on Refinery and Salvage. In 3 and 4 player count and non-Sabo/Elimination missions, increase Difficulty by 15/40%.
- When Non-Swarm Egg is pulled on Egg Hunt, x2 ECM.
- Sabotage: Reduce Turret Count by 1/3.
- Deep Scan: During Non-Solo Drillevator, SpeedModifier increased by 30%. 
- Revive HP and Maximum Regen Health: Increased 10% -> 30%. You start regen after 6s of not taking damage and take 10s to fully regen to Max Regen HP.
- During Dreadnought, a Dread wave that has limited spawn pool, 1/4 of the Normal Wave Size and guaranteed Bulk (As DreadHelper) will spawn in. This bulk takes slightly more damage and the weakpoint is more durable to help killing the Dreadnought faster. When the Bulk is killed, the Dread wave will respawn after 30/20/10s.
- During Sabotage fight, Normal Wave can continue to spawn in. In Solo, it takes slightly longer time to spawn.
- Enemy Changes:
  + Removed Prospector, Harold, Bet-C, Crassus Bulk, Tyrant-Weed as special encounters out of the game.
  + Youngling: MinSpawnCount limited to 1. Added SpawnSpread and NoSpawnWithin of 7.5m and 5m. Unable to Spawn during Drillevator. Rarity increased 4 -> 10/8. Unable to spawn in Encounters. Added Hidden Cooldown of 240s when Spawned.
  + Shellback: Added SpawnSpread and NoSpawnWithin of 7.5m and 5m. Unable to Spawn during Drillevator.
  + Shocker: MinSpawnCount limited to 1, MaxSpawnCount increased 15 -> 20. SpawnSpread 5m -> 15/10/5/5m. Added NoSpawnWithin of 5m. Rarity increased 4 -> 10/8. Unable to spawn in Encounters.
  + Grabber: Added NoSpawnWithin of 5m, SpawnSpread 5000. At non-Solo, Rarity lowered 15 -> 10. In Solo, Unable to be spawned in Encounters and MaxSpawnCount reduced to 0.
  + Swarmer: Capped MaxSpawnCount to 100.
  + Stalker: Damage Dealt reduced by 25%. Now is able to be Stunned at x1 duration and 2s Stun Immunity timer. Added Hidden Cooldown of 240s when Spawned. Unable to Spawn in Solo.
  + Stingtail: Rarity increased 4 -> 8. Unable to Spawn in Solo.
  + Shredder (Sabotage): Capped MaxSpawnCount to 20.
  + Vartok Scalebramble: DifficultyRating 100 -> 150. SpawnAmountModifier x1 -> x0.5. MaxSpawnCount reduce to 0 in Solo/Duo setting.
  + Bulk Detonator: Unable to Spawn during Drillevator, Blackbox/Uplink/Refill Bubble in Solo. In Solo, MaxSpawnCount reduced to 0, added Hidden Cooldown of 480s when Spawned, and Increase Dotty's Resistance by 40% when Bulk is present in Escort. In non-Solo, Rarity 15 -> 12 and reduce MaxSpawnCount to 0 During Blackbox/Uplink/Refill Bubble.
  + Acid Spitter and Web Spitter: Unable to be spawned in Encounters in Fungus Bogs (Unfair advantages due to ceiling foliages).
  + Goo Bomber: Unable to be spawned in Encounters in 6/8 Eggs, PE, Refinery and Deep Scan mission types.
  + Barrage Infector: DifficultyRating 145 -> 150. Capped MaxSpawnCount to 0/1/3. SpawnAmountModifier x1 -> x0.667.
  + Cave Leech: TentacleSpeed, Pull and RetractSpeed increased x1 -> x1.25 (Unable to stack with VEA). If a Leech from high up grabs you and it's killed, you will not die of fall damage (Except extreme cases).
  + Blackbox/Uplink/Refill Bubble in Solo: Reduce LeavePenalty by 25%.
  + Menace: At non-Solo, Rarity 10 -> 8.
  + Exploder: Unable to be spawned in Encounters in 6/8 Eggs, PE, Refinery and Deep Scan mission types. In DeepScan and PE, additionally unable to spawn in constant pressure waves at first 25s into mission.
  + Breeder Egg: Base EggHealth 120 -> 70/90/120.
  + Egg Spider: Only spawn 1 swarmer now.
  + Escort: Flying Rock Base Health: 250 -> 120.
  + All Dreadnought Bosses: They can now be ignited normally with 100 point (Dousing at 50).