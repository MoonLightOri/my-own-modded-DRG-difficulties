Penumbra (previously named FCM), is the *Modified* Hazard FC (made by pH-JPEG) with various tweaks to reduce bad RNG and balance more around mission types and enemies. This tweak is done by MoonLightOri and will mainly base on the tweaks from Interstellar 4 player count and on fire comp in general. This is updated to version v1.05.

Penumbra requirement: Custom Difficulty 2 Beta 14, MEV v5.4 and DEA (any version)
(But I recommend you to update DEA to latest version)

- Recommended Mods: 
  + VEA: https://mod.io/g/drg/m/vanilla-enemy-adjustments
  + No Special Swarms: https://mod.io/g/drg/m/no-special-swarms#3374117
  + Sabo with Stationaries & More Egg Swarms & Only Bug No Content (Use MINT to Install): https://drive.google.com/file/d/1-FPzfrHX7dozcD3BQX5VWSovlQ4jfwTR/view?usp=sharing
  + No Carve Exploder (Large exploder spam): https://cdn.discordapp.com/attachments/1148725752020340827/1189713606762303578/No_Carve_Exploders.pak?ex=67fe44e3&is=67fcf363&hm=a34e1174c13cdd3ce68ae891e94cc4ca7c757c8afbdbbc085f54911e175aa92c&
  + No Bulk Fragment Carve (Significantly higher Bulks spam than Celestial, you should have this): https://cdn.discordapp.com/attachments/1148725752020340827/1207731780405305364/no_bulk_fragments_carve.pak?ex=67fde69f&is=67fc951f&hm=83c11c061c3c43b6cbe28fc173f53b0d554a2d8caa37f9c633568891c7a9a494&

- Optional Mods:
  + Stalker Low Graphic Fix (If you can't play with high Effect setting): https://cdn.discordapp.com/attachments/1148725752020340827/1205500046557057055/StalkerLowGraphicsFix.pak?ex=67fe59e8&is=67fd0868&hm=97cb4a9dbca9553f1f5b720458a0e9f8d9d4ed943156c785e3d0c115dec793e0&
  
- Q: Why are Dread and Caretaker with normal wave mod not included in the recommended list above? 
  - A: My difficulty has a dedicated Wave Spawner to simulate normal waves during Dread and Caretaker with 100% accuracy. You don't need Dread and Caretaker with normal wave mod anymore since I've forced this into my difficulty.

* Legends: 
  + During Defense = Uplink/Refuel/Blackbox objectives.
  + 1/2/3/4 = Player Count setting (Left to Right, The last value in the list is used if there are more players than there are values in the list.).
  + 1p = 1 Player Setting.

Changelog compares to FC is below:

# General
- Banned Blood Sugar, Low Gravity, Duck and Cover, Ebonite Outbreak and Lithophage Outbreak warnings.
- During Defense, reduce Progress Bar Penalty by 30%, and Mission Control will no longer shout when no player is at the bubble zone.
- Added NitraMultiplier for Mission types with values:
  > Mission type (Complexity:Length): Value
    + Mining    (1:2): x1.15 (~2/3 a resupply, ~40N)
    + Elim      (2:2): x1.2 (enough for 1 more resup, ~60N)
    + Deep Scan (2:1): x1.2 (enough for 1 more resup, ~60N)
    + Sabotage  (1:2): x1.35 (slightly over 2 resups, > 120N)
    + Sabotage  (2:2): x1.1 (just enough for 1 more resup, ~60N)
- Added NitraMultiplier for Deep Dive Secondaries with approximate values: 
    + 1 Extra resupply (~60N) on Eggs, Dreadnought Cocoon and Black Box.
    + 0.4 Extra resupply (~25N) on Deep Scan and Morkite Well.
    + Unchanged in Mini-Mules and Morkite.
    + Side Note: This value is also compatible with current Main objective if they have nitra multiplier support, calculated additively.
- Rival Turrets spawn count in Encounters sabotage mission type is reduced by 50%.
- EnemyWaveInterval: 1% chance to instantly spawn an announced wave is now restricted to during hotdrop of Refinery mission type, and it will delay 7s to spawn an announced wave instead.
- EnemyNormalWaveInterval: Removed 10% chance to instantly spawn a normal wave.
- Restructured VeteranLarge promotion, now use CustomVeterans code on Praetorians to prevent overspawning Oppressors issue previously.

# Enemies (Detail changes)
- Weak Twins: Added 45s Cooldown. They are now banned during Dreadnought due to unexpected behaviors.
- Mini Bulk, Normal Bulk, Plantonator: Reduced MaxSpawnCount to 0 and Added Nospawnwithin of 7.5m and cooldown of 120s during Uplink/Refill/Blackbox, additionally during Escort Refill and Heartstone for MiniBulk and Normal Bulk. Otherwise cooldown is 60s. Plantonator is additionally banned during Drillevator.
- Big Bulk: Added Corrosive Damage Weakness of 150%, NoSpawnWithin 7.5m and have cooldown of 1 hour on Refinery, Salvage and 4/6 Eggs. Otherwise cooldown is 900s (15 minutes). They are additionally banned during Drillevator.
- Mactera Warden: DifficultyRating 100 -> 135 (Since they are very oppressive in OG FC).
- Breeder type enemies: FreezeTemperature -300 -> -150.
- Gorilla: AttackDamageMultiplier x1 -> x1.4. Immune to being Feared.
- Grabber: Added NoSpawnWithin 5m.
- Big Shocker: AttackDamageMultiplier x1 -> x2. Immune to being Feared. Frozen temperature is increased to -240 due to DieIfFrozen not working at all.
- Flying Rock from Escort Heartstone: HP reduced from 250 -> 148 (Slasher base HP).
- Elite Mactera Spawn: AttackDamageMultiplier x1 -> x0.9. TimeDilation x1 -> x0.85.
- Patrol Bot: FreezeTemp and Unfreeze temp are now reduced. When frozen, increase x3 damage taken.
- Rockpox Septic: AttackDamageMultiplier 1 -> 0.75.
- Sentinel: DifficultyRating 50 -> 60. Movement speed buff x1.35 -> x1.25. Added Electric Damage Weakness by -30%. No longer spawns on Encounters.
- Trawler (from pool & wavespawner): No longer spawns during Encounters, TimeDilation x1 -> x0.75. In 1p setting it's banned from spawning.
- Big Shredder: Reverted all weaknesses back to x1 value. AttackDamageMultiplier x1 -> x2. Immune to being Feared. Frozen temp is now -240.
- Weak Lacerator: Now use Base Descriptor "ED_Lassie_Zen".
- Weak Elites: They now have reduced Burn and Frozen temperature (still x2 higher than normal enemy type).
- Acid Spitter: Changed material to make it easier to see in the dark. AttackDamageMultiplier x1 -> x0.8.
- Web Spitter: UsesBiomeVariants = false.
- Stingtail: Rarity 5.25 -> 5.5.
- Sprouts (Ground and Ceiling): Changed material to make it easier to see in the dark. 
- Youngling: CanBeUsedForConstantPressure = false.

# Custom Waves
- Removed Canary WaveSpawner.
- During Dreadnought or Caretaker fight, Normal Wave will spawn in periodically. For Dreadnought fight, the Interval is increased by 50, but the beginning of the fight will guarantee a Normal Wave spawn.
- During a Caretaker fight, a Weak Bulk Detonator known as a "CaretakerHelper" with slower movement speed and Base HP x0.25 will spawn in to allow the team to speed up Caretaker fight. It has halved carve radius compare to Normal Bulk. Only one CaretakerHelper can exist at a given time. Its material is slightly changed to distinct from Bulks that spawn from Waves.
- Grunt WaveSpawner: Interval during Dread, RefineryStalled, Escort Refill and Caretaker is increased to 60s. No longer spawns minibulks during Uplink/Refill/Blackbox and Drillevator.
- Trawler WaveSpawner: Limit the amount of XED_Shark on the map to 5. ED_Shark from pool spawn doesn't count toward this. This WS is disabled in 1p setting to avoid frustration.
- Weak Elite WaveSpawner: Interval during Dread, RefineryStalled, Escort Refill and Caretaker is increased to 100s.
