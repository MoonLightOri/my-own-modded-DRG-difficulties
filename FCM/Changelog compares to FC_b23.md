FCM, is the *Modified* Hazard FC (made by pH-JPEG) with various tweaks to reduce bad RNG and balance more around mission types and enemies. This tweak is done by MoonLightOri and will mainly base on the tweaks from Interstellar 4 player count and on fire comp in general. This is updated to version v1.04. Changelog compares to FC is below:

# General
- Banned Blood Sugar, Low Gravity, Duck and Cover, Ebonite Outbreak and Lithophage Outbreak.
- During the time of Uplink/Refuel/Blackbox objectives, penalty of draining the progress bar is reduced by 30%, and Mission Control will no longer shout when no player is at the bubble zone.
- Added NitraMultiplier for Mission types with values: +55% on Sabotage 1 Complexity, +35% on Elimination 2 Dreads, +20% on Mining 225 Morkite, Deep Scan 3 Crystals, Sabotage 2 Complexity and +10% on Elimination 3 Dreads.
- Added NitraMultiplier for Deep Dive Secondaries with values: +25% on Eggs and Dreadnought Cocoon, +20% on Black Box, +10% on Deep Scan and Morkite Well, unchanged in Mini-Mules and Morkite. This value is also compatible with current Main objective if they have nitra multiplier support, calculated multiplicatively.
- Sabotage mission type: -50% Rival Turret spawn amount.
- EnemyWaveInterval: 1% chance to instantly spawn an announced wave is now restricted to during hotdrop of Refinery mission type, and it will delay 7s to spawn an announced wave instead.
- EnemyNormalWaveInterval: Removed 10% chance to instantly spawn a normal wave.
- Restructured VeteranLarge promotion, now use CustomVeterans code on Praetorians to prevent overspawning Oppressors issue previously.

# Enemies
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
- Added DreadNWave and CaretakerNWave with 180s/140s interval (the beginning of dread fight will have a normal wave immediately), this is to simulate Dread and Caretaker with wave mod.
- Grunt WaveSpawner: Interval during Dread, RefineryStalled, Escort Refill and Caretaker is increased to 60s. No longer spawns minibulks during Uplink/Refill/Blackbox and Drillevator.
- Trawler WaveSpawner: Limit the amount of XED_Shark on the map to 5. ED_Shark from pool spawn doesn't count toward this. This WS is disabled in 1p setting to avoid frustration.
- Weak Elite WaveSpawner: Interval during Dread, RefineryStalled, Escort Refill and Caretaker is increased to 100s.
