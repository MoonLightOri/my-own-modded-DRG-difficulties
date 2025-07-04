This difficulty used ND - a difficulty made by pH-JPEG, as a framework, but with adjustments. It's also a toned-down version of Interstellar. Updated to v1.02.

Contributor: seu

Celestial minimum requirement: Custom Difficulty 2 beta 15, MEVv5_4, DEA_a05t2+ (Latest version is always better).

- Recommended Mods: 
  + VEA: https://mod.io/g/drg/m/vanilla-enemy-adjustments
  + No Special Swarms: https://mod.io/g/drg/m/no-special-swarms#3374117
  + Sabo with Stationaries & More Egg Swarms & Only Bug No Content & No Crawler Puddles (Use MINT to Install): https://drive.google.com/drive/folders/1E4UR8TwjofQM-b4SRm-pOf0bq4_qoYfL?usp=sharing
  + No Carve Exploder (Large exploder spam): https://cdn.discordapp.com/attachments/1148725752020340827/1189713606762303578/No_Carve_Exploders.pak?ex=67fe44e3&is=67fcf363&hm=a34e1174c13cdd3ce68ae891e94cc4ca7c757c8afbdbbc085f54911e175aa92c&

- Optional Mods:
  + Stalker Low Graphic Fix (If you can't play with high Effect setting): https://cdn.discordapp.com/attachments/1148725752020340827/1205500046557057055/StalkerLowGraphicsFix.pak?ex=67fe59e8&is=67fd0868&hm=97cb4a9dbca9553f1f5b720458a0e9f8d9d4ed943156c785e3d0c115dec793e0&
  + No Bulk Fragment Carve (Higher of Bulks spam): https://cdn.discordapp.com/attachments/1148725752020340827/1207731780405305364/no_bulk_fragments_carve.pak?ex=67fde69f&is=67fc951f&hm=83c11c061c3c43b6cbe28fc173f53b0d554a2d8caa37f9c633568891c7a9a494&
  + More Egg Swarms (If you want a more challenging Egg Hunt): https://cdn.discordapp.com/attachments/1148725752020340827/1166128615440789546/more_egg_swarms_P.pak?ex=682ef0a7&is=682d9f27&hm=c21d0b1a6b76339885f8070ee82a954dd027619df1506a39824f347f1fdd8b42&
  
- Q: Why are Dread and Caretaker with normal wave mod not included in the recommended list above? 
  - A: My difficulty has a dedicated Wave Spawner to simulate normal waves during Dread and Caretaker with 100% accuracy. You don't need Dread and Caretaker with normal wave mod anymore since I've forced this into my difficulty.

* Legends: 
  + During Defense = Uplink/Refuel/Blackbox objectives.
  + 1/2/3/4 = Player Count setting (Left to Right, The last value in the list is used if there are more players than there are values in the list.).
  + 1p = 1 Player Setting.

# General (Mostly the same as ND)
- Enemy Damage and Movement Speed scaling follows Hazard 7. Enemy HP scaling stays at Hazard 6 instead.
- Enemy Count Modifier values are 7x2 values.
- Initial resupply cost is 40 nitra, afterwards it raises to 50 nitra.
- Enemy projectile speed follows Hazard 6.
- Friendly fire is set to 110%.
- You revive with 40% HP and regen up to 40% of your HP compared to the typical 10% seen in Hazard 5 and other modded Hazards. You begin to regenerate your HP after 6 seconds if you don't take any damage. It takes 10 seconds to regenerate from 1 HP to 40% HP once the regeneration begins.
- Dorretta resists 81.25% of damage (Higher in Solo in certain scenarios); The resistance value is higher than 6x2.
- During the Extraction phase of a mission or the PE countdown until the Drop Pod lands, x1.35 or x1.6 more bugs spawn respectively.
- During the time in-between the Fuel Cells and the Drop Pod opening on a Salvage mission, there will initially be a pause in bug spawns with the amount of bugs spawning greatly increasing as the Drop Pod gets closer to opening.
- Whenever an Egg is pulled, if it does not trigger a swarm, the wave it summons spawns x3 the bugs.
- Wave timers are technically based off of Hazard 7.
- A "fat" wave of bugs can rarely spawn. This is a wave that is twices the size of a typical wave.
- Enemy diversity is higher and more variable; this means you can get multiple types of enemies all spawning at once with the amount being variable. You could get a superdiverse wave or a wave of only one or two enemy types.
- Most caves will have at least one of every Stationary type if possible.
- Veteran chance has been significantly increased; this means more Guards, Slashers, Brundles, Trijaws, and Oppressors. Some of the enemies can also be promoted into new type of enemies, with own's custom veterans chance.
- Many new enemies have been added in the form of enemies that normally don't spawn in waves and entirely new enemies from CD2, MEV and DEA.
- Some existing enemies have been modified (E.G: Some enemies having lower freezing temperatures like Breeders, Bombers and Patrol Bot. Elite enemies have lower burn and freeze temperature,... - Having some favor for Cryo comp.).
- Custom waves of certain enemies spawn at set intervals or conditions.
- Difficulty adjusted across mission types (E.G: PE gets slightly harder, Escort heartstone phase gets slightly easier).
- During Defense, reduce Progress Bar Penalty by 30%. At 1p, also increase Bubble radius by 40%.
- Rival Turrets spawn count in Encounters sabotage mission type is reduced by 50%.
- Lower player scaling (Especially Solo) will have signficant change on Enemies, Objectives and Mission types to make playing easier. (E.G: Doretta during Refill and Heartstone phase gains slight increased resistance. No Bulk spawns during Defense...)
- Added NitraMultiplier for Deep Dive Secondaries with approximate values: 
  + 1 Extra resupply (~50N) on Eggs, Dreadnought Cocoon and Black Box.
  + 0.4 Extra resupply (~20N) on Deep Scan and Morkite Well.
  + Unchanged in Mini-Mules and Morkite. For Mini-Mules secondaries, Nitra Reward from Reparing is reduced from 50 -> 30 Nitra, but Scanning and Repair Time are reduced by -33.3%. Unaffected in Salvage mission type.
- Disabled player headbounces.
- Banned Blood Sugar, Low Gravity, Duck and Cover, Ebonite Outbreak and Lithophage Outbreak warnings.

# Enemies
- Swarmer
  + They are now stunnable.
  + Base HP 12 -> 4.
- Sentinel
  + They are the bugs the Dreadnought Hiveguard summon. Electric Weakness +30%.
- Leech
  + They grab and damage +60% faster.
  + However, if a Leech from high up grabs you and it's killed, you will not die of fall damage.
- Fire Bomber
  + They are an unused enemy in the game files. They behave like a normal Goo Bomber, except they drop bomblets that deal extreme damage to players.
- Fire Praetorian
  + They are another Praetorian variant from MEV. Has different coloring than normal's.
  + Base HP 700 -> 450. They move +50% faster.
  + Has an even lower stun duration and higher stun immunity window than normal Praetorian. Immune to Fear.
  + Their spitting attack will deal fire damage with higher damage value.
  + Their death gas cloud is replaced with Incendiary flame trail (has lower radius than Gas), they will damage you with fire damage and heat you up.
- Acid Spitter
  + Their Direct hit damage -10%, and have slight material change.
- Breeder
  + They have Base HP -50%. 
  + A Breeder can sometimes respawn in a wave.
  + They now instead spawn White Exploders that move -25% slower.
  + They are rarer in Escort.
- Patrol Bot
  + They spawn globally independent of Rival Presence or Industrial Sabotage.
  + No longer do Bump Attack (You take damage and get knocked back).
- Nexus
  + They have Fire Damage Weakness +295%. 
  + They now instead spawn white Slashers that only have ~66 HP.
- White Exploder (MEV)
  + Only spawns from Normal Breeders.
  + They also move -25% slower.
- Exploder
  + They move +50% faster.
- Grabber
  + They spawn spread out from waves. There is 33.3% chance to promote into Deliverer instead.
  + They move +50% faster.
- Deliverer (CD2)
  + They move -30% slower and have Fear immunity. Their materials are changed slightly.
  + They won't flee away or drop you down after taking damage.
- Bulk Detonator
  + They move +50% faster. 
  + They also tend to spawn far from the team. On an Escort, they spawn at a normal distance from the team.
- Ice Detonator (MEV)
  + They move +50% faster, and is slightly rarer than Bulk Detonator.
  + Stomp and Explosion damage type changed to Cold damage, which will instantly freeze you.
  + Leave no Meetball on Explosion but have a larger damage range and blast player away.
- Flying Rock from Heartstone phase
  + Base HP 250 -> 90/120/148 (same Base HP as Grunt/Acid Spitter/Slasher).
- Trawler (Spawn on Sandblasted)
  + They have Time Dilation -25%. 
  + Maximum spawn on field reduced to 0/2/4/5.
  + Banned in 1p.
- Oppressor
  + They move +50% faster. 
  + Maximum spawn on field reduced to 2, and 1 during Defense and Hacking. At 1/2p, this number in both scenarios is reduced by 1.
- Stalker (Beta Stalkers from MEV)
  + They are replaced with their Beta version. 
  + Set your Effects in the in-game options to High to see them while they are cloaked. If you have Low Graphic Stalker Fix mod then you can ignore this line.
  + No longer spawns in Solo.
- Naedocyte Seeder (CD2)
  + It's a rarer Breeder that is bigger sized and only spawns in a wave (Highlighted by Enemy Outline, disappear after being pinged by player and expire). Their materials are changed also.
  + Base HP & movement speed -66.66%.
  + They now instead spawn smaller and different look Sentinels that inherit every trait of normal Sentinel (Except bonus movement speed), with some extra stats: Fire damage resistance +25%, Base HP -40%, and Damage Dealt -25%.
  + It will bleed out (lose HP) after 2 minutes of being in the map and dies exactly 2 minutes later (The timer value is lower in player count).
- Elite Guard, Elite Grunt Slasher, Elite Septic Spreader and Elite Ratter (CD2 - DEA)
  They spawn globally independent of Elite Threat, and mostly spawn via custom Wave Spawner. Individual changes are below: 
  - All Elite enemies except Guard have material change (to tell them if they are weak).
  - Elite Slasher: Has 265/274/309/336 HP (based on Crawler Normal Scaling at 4p).
  - Elite Ratter (DEA):
    + They are ground Acid Spitter that lob a projectile that spawns 1 Glyphid Rat (Detail below)
    + Has 140/145/164/177.6 HP (based on Slasher Normal Scaling at 4p).
    + Additionally, movement Speed now +50%.
  - Elite Septic: Has 114/117/133/144 HP (based on Acid Spitter Normal Scaling at 4p). Additionally, Time Dilation +30% and Damage Dealt -20%.
  - Elite Guard: Has 967/999/1128/1225 HP (based on Menace Special Scaling at 4p). THEY ONLY SPAWN IN WAVES.
- Glyphid Rat: 
  + They are bigger sized Swarmer that won't die when ignited/frozen. Their materials are changed also.
  + Base HP 12 -> 20, move +20% faster and Damage Dealt +50% than normal Swarmer.
  + There are variants that spawn only on swarmer tunnel and glyphid egg, they are named as Glyphid Sewer/Hatched Rat, have Base HP 12 -> 50 instead, 50% resistance to Fire Damage and Fear Immunity. They also have Different base materials.
- Mactera Plague Bomber (DEA)
  + These are Goo Bomber variant that have Base HP -25%. Their materials are changed also.
  + Normal attack projectile is now replaced with Glyphid Dreadnought's Eggshot projectile that spawns a bunch of Glyphid Rats and apply Pheromone STE.
  + Bombing attack now spawns individual Glyphid Rats instead.
  + On its presence, all Glyphid Rats on-field (Except Sewer/Hatched Rats) gain +60% Damage Resistance (Reflected by Blacker material change). This buff is removed when all on-field Plague Bombers are dead.
- Glyphid Dreadnought (BOSS)
  + Glyphid Dreadnought's Eggshot projectile spawns a bunch of Glyphid Rats instead with Pheromone STE.
- Turbo Menace (MEV)
  + They are flashy Menaces from MEV that have Base HP 800 -> 100.
  + Instead, they shoot a laserbeam of projectiles.
- Glyphid Architect (CD2)
  + It is a rare menace variant that has Base HP x0.7855 and Time Dilation -25%. Its material is changed also.
  + Normal projectile is now the default (No Upgrade) Engineer's Platform. Its purpose is to disrupt surrounding terrain around players.
- Lacerator + Arbalest (DEA)
  + They can spawn in waves that have Base HP of 600 (Brundle's). 
  + They will not try to heal with each other so burrow and fireballs pan attacks are locked.
  + In 1p setting, Arbalest cannot be spawned during Drillevator.
- Mini Bulk Detonator (MEV)
  + They are small Bulk Detonators from MEV that have Base HP x0.3292. 
  + None of normal Bulk SFX will be played until they die, so they are more stealthy than Normal Bulk.
  + Their stomp radius and explosion radius are significantly smaller than normal Bulk's. Meatball count upon death is reduced as well.
- Line-Cutting Turret (CD2)
  + They are Repulsion Turrets that have their materials changed and now shoot slow Breach Cutter projectile.
  + Stationary unit.
  + Burning won't self-destruct them. Burning and Freezing temperature is now lower than normal.
  + It cannot be spawned on Escort mission type.
- Rocket Turret (CD2, MEV)
  + They are Sniper Turrets that have their materials changed and now shoot Patrol Bot's homing missile projectiles that deal +50% more damage.
  + Stationary unit.
  + They are slightly rarer in Escort.
- Korlok Sprouts (MEV)
  + Stationary unit.
  + They can spawn only on the ground and start off sleeping until they take damage.
  + Base HP -1/6. Its material is slightly changed to shine in the dark.
- Nukeballer (MEV)
  + They are more expensive Spitballers from MEV that have different look.
  + Stationary unit.
  + Projectile they shoot is a slow-moving nuke that instakills anyone in the blast radius and leaves behind a cloud of radiation.
  + The projectile does not carve terrain and can be shot down.
- Spitscreener (CD2, MEV)
  + They are more expensive Spitballers that have Time Dilation -33.33%. Their materials is changed also.
  + Stationary unit.
  + Projectile they shoot is triple Nemesis's barriers.
- Big Shredder (CD2)
  + They spawn in a pair. Base HP x12.82, Damage Dealt +100% and is immune to Fear.
  + They don't have any weaknesses of small shredders.
- Vomit Spitter (CD2, DEA)
  + They are ground Web Spitter that spit Barrager's vomit projectile in an arc. Their materials is changed also.
  + Use Acid Spitter's AI, mean that they will aggressively shoot at you once they stop moving.
  + They have improved accuracy compare to Astral difficulty's version.
- Barrier Shooter (CD2)
  + They are Acid Spitter that spit Nemesis's barrier. Their materials is changed also.
  + Use Web Spitter's AI, mean that they will reposition after shootting once.
  + They move +50% faster.
- Crawler
  + They can spawn in waves globally independent of the Core Stone event.
- Barrage Infector
  + They are rarer than usual and are even rarer on Escort.
- Nuke Barrager (CD2, DEA)
  + They are more expensive Barragers that have Time Dilation -66.66% (Even slower Time Dilation when spawned in the first 20s into the Mission). Their materials is changed also.
  + Stationary unit.
  + Projectiles they shoot are low velocity Fat Boy nukes that instakill anyone in the blast radius and leave behind a cloud of radiation.
  + The projectiles WILL carve terrain and CANNOT be shot down.
  + Only one can spawn in Refinery and Escort. In 1p setting, this applies for every mission types.
- Scalebramble (CD2)
  + They are rarer than usual. Only one can spawn on Escort. They are time dilated to half speed.
- The Sun (CD2)
  + This is a static Ommoran Flying Rock that has Base HP 300. Its material is changed also.
  + On its presence (Highlighted by Enemy Outline, disappear after being pinged by player and expire), it increases Movement Speed, Projectile Speed and decreases Attack Cooldown (apply mostly for Melee attack enemies like Grunt) values by a considerable amount.
  + It cannot buff already on-field enemies before The Sun spawns. The buff cannot wear off on already buffed enemies.
  + The Sun will bleed out (lose HP) after 45s of being in the map and dies exactly 45s later (The timer value is lower in player count). 
  + It cannot be spawned During Defense, Drillevator and Escort mission type.
- The Moon (CD2)
  + This is a static Ommoran Flying Rock that has Base HP 300. Its material is changed also.
  + On its presence (Highlighted by Enemy Outline, disappear after being pinged by player and expire), it prevents regen your HP naturally, reduces revive HP to 10% and reduces all lighting values to low amount (This will make surrounding much darker).
  + The Moon will bleed out (lose HP) after 45s of being in the map and dies exactly 45s later (The timer value is lower in player count).
  + It cannot be spawned During Defense, Drillevator and Escort mission type.
- Q'ronar Ninja (CD2, MEV)
  + They are Shellback variant that are smaller scaled and spawn far away from the team. Their materials are changed also.
  + Base HP is the same as Tri-jaw Normal Scaling At 4p, so lower player count gets lower HP. 
  + Damage taken stats: Electricity x1.2, Physical x2 (Weak) and Fire x1.
  + Their AI have been tweaked to have instant walking speed (Teleport) and rarely roll around. Which mean they will do more spit attack than Shellback normally.
  + They do only x0.15 contact damage (No knockback and damage RNG) with slightly lower range when they roll. Their projectile is fused with Electricity STE, but their damage dealt -67%.
 

# Custom Waves
- During a Dreadnought fight (OG Dreadnought, Hiveguard, normal Twins), a Bulk Detonator known as a "DreadHelper" with Base HP x0.85 will spawn in to allow the team to kill the Dreadnought faster (Highlighted by Item Outline, disappear after being pinged by player and expire). Only one DreadHelper can exist at a given time.
- During a Caretaker fight, a Weak Bulk Detonator known as a "CaretakerHelper" with slower movement speed and Base HP x0.25 will spawn in to allow the team to speed up Caretaker fight (Highlighted by Item Outline, disappear after being pinged by player and expire). It has halved carve radius compare to Normal Bulk. Only one CaretakerHelper can exist at a given time. Its material is slightly changed to distinct from Bulks that spawn from Waves.
- During Dreadnought or Caretaker fight, Normal Wave will spawn in periodically. For Dreadnought fight, the Interval is increased by 50, but the beginning of the fight will guarantee a Normal Wave spawn.
- Every 110 seconds (Longer during certain pressure scenarios), either 14-20 non-promoted Grunts (Not promoted into veterans) or 2-3 Mactera Spawns spawn. The chance they spawn is split into 80%/20%.
- Every 80 seconds (Longer during certain pressure scenarios), a mix of 2-4 weak Elite enemies will appear. The pool are: 1-2 Slashers, 1 Septic Spreader and 1-2 Ratters. Septic Spreader has a moderate cooldown timer after they spawned.

# Miscellaneous:
- Bandaid bug fix: Darkness module somehow caused scout's flare gun to have significantly less duration time so I added FlareGunDuration field value in Darkness module file, so it matches 90s of duration (1 duration upgrade) most scout upgrade path will take.
