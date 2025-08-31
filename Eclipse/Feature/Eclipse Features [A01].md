This difficulty used Interstellar and Send It! Type R as a framework, but with adjustments. Initial Alpha 01 release.

Contributor: seu (for certain enemies)

Interstellar requirement: Custom Difficulty 2 beta 15b, MEVv5_4, DEA_b003.3. (Latest version is always better)

- Recommended Mods: 
  + VEA: https://mod.io/g/drg/m/vanilla-enemy-adjustments
  + No Special Swarms: https://mod.io/g/drg/m/no-special-swarms#3374117
  + Sabo with Stationaries & More Egg Swarms & Only Bug No Content & No Crawler Puddles (Use MINT to Install): https://drive.google.com/drive/folders/1E4UR8TwjofQM-b4SRm-pOf0bq4_qoYfL?usp=sharing
  + No Carve Exploder (Large exploder spam): https://cdn.discordapp.com/attachments/1148725752020340827/1189713606762303578/No_Carve_Exploders.pak?ex=67fe44e3&is=67fcf363&hm=a34e1174c13cdd3ce68ae891e94cc4ca7c757c8afbdbbc085f54911e175aa92c&
  + No Bulk Fragment Carve (Significantly higher Bulks spam than Celestial, you should have this): https://cdn.discordapp.com/attachments/1148725752020340827/1207731780405305364/no_bulk_fragments_carve.pak?ex=67fde69f&is=67fc951f&hm=83c11c061c3c43b6cbe28fc173f53b0d554a2d8caa37f9c633568891c7a9a494&

- Optional Mods:
  + Stalker Low Graphic Fix (If you can't play with high Effect setting): https://cdn.discordapp.com/attachments/1148725752020340827/1205500046557057055/StalkerLowGraphicsFix.pak?ex=67fe59e8&is=67fd0868&hm=97cb4a9dbca9553f1f5b720458a0e9f8d9d4ed943156c785e3d0c115dec793e0&
  + More Egg Swarms (If you want a more challenging Egg Hunt): https://cdn.discordapp.com/attachments/1148725752020340827/1166128615440789546/more_egg_swarms_P.pak?ex=682ef0a7&is=682d9f27&hm=c21d0b1a6b76339885f8070ee82a954dd027619df1506a39824f347f1fdd8b42&

* Legends: 
  + During Defense = Uplink/Refuel/Blackbox objectives.
  + 1/2/3/4 = Player Count setting (Left to Right, The last value in the list is used if there are more players than there are values in the list.).
  + 1p = 1 Player Setting.

# General Gameplay (Mostly the same as Send It! Type R)
- Announced Waves no longer spawns (Except in certain forced mission type), instead Normal Wave with Small Size are frequently spawned (90% will be main timing - covered soon, 10% for the longer 60s bin).
- The game will start ticking down the Threat Meter (Displayed as boss bar) after 15s of starting. There are 5 levels of Threat which increase the difficulty, interval and enemy composition of Normal Wave. Every phase transition (or looping in Lv5) will force spawn a normal sized wave (which can stack with the current Normal Wave spawner). Here's the detailed section for each threat:
  + Threat Lv1: LOW. Take 180s to reach Lv2. Main Normal Wave timing is 45s.
  + Threat Lv2: MODERATE. Take 270s to reach Lv3. Main Normal Wave timing is 35s. Some Enemies are now able to spawn (Fire Bomber, Sentinel, Naedocyte Breeder in Swarm, Patrol Bot, Architect, Barrier Shooter, Vomit Spitter). Bulk Detonator now moves 35% faster.
  + Threat Lv3: SUBSTANTIAL. Take 360s to reach Lv4. Main Normal Wave timing is 30s. Some Enemies are now able to spawn (The Sun & Moon, Elite Grunt Guard, Turbo Menace, Mini-Bulk, Ninja, Naedocyte Seeder). Bulk Detonator now moves 35% -> 50% faster. Nexuses now spawn White Weak Slasher (previously White Weak Grunt). Swarmer Tunnel and Egg Spider now spawn tanky Glyphid Rat enemies (Previously White Weak Grunt). Naedocyte Breeder now spawn White Exploder. Normal Exploder and Grabber now moves 50% faster. Oppressor moves 20% -> 50% faster. Every 90s, Lacerator or Arbalest will spawn via Mini-Boss WaveSpawner. Enemy Movement Speed increases from Hazard 6 value to Hazard 7.
  + Threat Lv4: SEVERE. Take 450s to reach Lv5/Max. Main Normal Wave timing is 27s. Fanatic and Grenade Spitter are able to spawn. Septic can now be promoted into Ice Septic variant. Youngnought and Ice Youngnought are now able to spawn via Mini-Boss WaveSpawner. Enemy Attack Cooldown (mostly for grunt) increases from Hazard 6 to Hazard 7.
  + Threat Lv5/Max: CRITICAL. Take 540s to refresh itself. Main Normal Wave timing is 25s. Mactera Warden, Rat Bomber and Barrinator are now able to spawn. Oppressor now moves 50% -> 100% faster. Grabber can now be promoted into Deliverer. Solaris and Joker are now able to spawn via Mini-Boss Wave Spawner. Enemy Damage Modifier increases from Hazard 6 to Hazard 7.
- For every 40 Gold into Team Repository (Counted by dividing 40 in repository) will increase the gauge by 90s immediately. This is crucial to delay the timer.

# New Enemies compare to Interstellar:
- Grenade Spitter: 
  + It's a rare Acid Spitter variant
  + Instead of spitting Acid projectile, it spits Gunner's Grenade, deal moderate damage in an AOE range.
