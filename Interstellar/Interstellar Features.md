This difficulty used FC_b23 - a difficulty made by pH-JPEG, as a framework, but with adjustments. Updated to v1.01.

Contributor: seu

Interstellar requirement: Custom Difficulty 2 beta 15, MEVv5_4, DEA_b003.3. (Latest version is always better)

- Recommended Mods: 
  + VEA: https://mod.io/g/drg/m/vanilla-enemy-adjustments
  + No Special Swarms: https://mod.io/g/drg/m/no-special-swarms#3374117
  + Sabo with Stationaries & More Egg Swarms & Only Bug No Content & No Crawler Puddles (Use MINT to Install): https://drive.google.com/drive/folders/1E4UR8TwjofQM-b4SRm-pOf0bq4_qoYfL?usp=sharing
  + No Carve Exploder (Large exploder spam): https://cdn.discordapp.com/attachments/1148725752020340827/1189713606762303578/No_Carve_Exploders.pak?ex=67fe44e3&is=67fcf363&hm=a34e1174c13cdd3ce68ae891e94cc4ca7c757c8afbdbbc085f54911e175aa92c&
  + No Bulk Fragment Carve (Significantly higher Bulks spam than Celestial, you should have this): https://cdn.discordapp.com/attachments/1148725752020340827/1207731780405305364/no_bulk_fragments_carve.pak?ex=67fde69f&is=67fc951f&hm=83c11c061c3c43b6cbe28fc173f53b0d554a2d8caa37f9c633568891c7a9a494&

- Optional Mods:
  + Stalker Low Graphic Fix (If you can't play with high Effect setting): https://cdn.discordapp.com/attachments/1148725752020340827/1205500046557057055/StalkerLowGraphicsFix.pak?ex=67fe59e8&is=67fd0868&hm=97cb4a9dbca9553f1f5b720458a0e9f8d9d4ed943156c785e3d0c115dec793e0&
  + More Egg Swarms (If you want a more challenging Egg Hunt): https://cdn.discordapp.com/attachments/1148725752020340827/1166128615440789546/more_egg_swarms_P.pak?ex=682ef0a7&is=682d9f27&hm=c21d0b1a6b76339885f8070ee82a954dd027619df1506a39824f347f1fdd8b42&
  
- Q: Why are Dread and Caretaker with normal wave mod not included in the recommended list above? 
  - A: My difficulty has a dedicated Wave Spawner to simulate normal waves during Dread and Caretaker with 100% accuracy. You don't need Dread and Caretaker with normal wave mod anymore since I've forced this into my difficulty.

* Legends: 
  + During Defense = Uplink/Refuel/Blackbox objectives.
  + 1/2/3/4 = Player Count setting (Left to Right, The last value in the list is used if there are more players than there are values in the list.).
  + 1p = 1 Player Setting.

# General (Mostly the same as FC)
- Enemy Damage and Movement Speed scaling follows Hazard 7. Enemy HP scaling stays at Hazard 6 instead.
- Enemy Count Modifier values are 7x2 values.
- Initial resupply cost is 40 nitra, afterwards it raises to 60 nitra.
- Enemy projectile speed follows Hazard 6.
- Friendly fire is set to 110%.
- You revive with 40% HP and regen up to 40% of your HP compared to the typical 10% seen in Hazard 5 and other modded Hazards. You begin to regenerate your HP after 6 seconds if you don't take any damage. It takes 10 seconds to regenerate from 1 HP to 40% HP once the regeneration begins.
- Dorretta resists 81.25% of damage (Higher in Solo in certain scenarios); The resistance value is higher than 6x2.
- During the Extraction phase of a mission or the PE countdown until the Drop Pod lands, x1.66 or x2 more bugs spawn respectively.
- During the time in-between the Fuel Cells and the Drop Pod opening on a Salvage mission, there will initially be a pause in bug spawns with the amount of bugs spawning greatly increasing as the Drop Pod gets closer to opening.
- Whenever an Egg is pulled, if it does not trigger a swarm, the wave it summons spawns x4 the bugs.
- Wave timers are significantly tighter than Celestial (Announced Wave value is loosely based off Chinese Hazard 11+, while Normal Wave value is harder than Chinese Hazard 15+), with 1% chance to have announced swarm to spawn instantly, only in beginning of Refinery mission type.
- A "fat" wave of bugs can rarely spawn. This is a wave that is twices the size of a typical wave.
- Enemy diversity is higher and more variable; this means you can get multiple types of enemies all spawning at once with the amount being variable. You could get a superdiverse wave or a wave of only one or two enemy types. Diversity wave setting is 1 value higher than Celestial's. 
- Most caves will have at least one of every Stationary type if possible.
- Veteran chance has been significantly increased; this means more Guards, Slashers, Brundles, Trijaws, and Oppressors. Some of the enemies can also be promoted into new type of enemies, with own's custom veterans chance.
- Many new enemies have been added in the form of enemies that normally don't spawn in waves and entirely new enemies from CD2, MEV and DEA.
- Some existing enemies have been modified (E.G: Some enemies having lower freezing temperatures like Breeders, Bombers and Patrol Bot. Elite enemies have lower burn and freeze temperature,... - Having some favor for Cryo comp.).
- Custom waves of certain enemies spawn at set intervals or conditions.
- Difficulty adjusted across mission types (E.G: PE gets harder, Escort heartstone phase gets slightly easier).
- During Defense, reduce Progress Bar Penalty by 30%. At 1p, further reduce Progress Bar Penalty to 60%, and 100% if the player is Scout (No more draining). Also increase Bubble radius by 50% at 1p.
- Rival Turrets spawn count in Encounters sabotage mission type is reduced by 50%.
- Lower player scaling (Especially Solo) will have signficant change on Enemies, Objectives and Mission types to make playing easier. (E.G: Doretta during Refill and Heartstone phase gains slight increased resistance. No Bulk spawns during Defense. Dangerous run ending at 1p also gets reduced specific values,...)
- Added NitraMultiplier for Mission types with values: 
  > Mission type (Complexity:Length): Value
    + Mining    (1:2): x1.15 (~2/3 a resupply, ~40N)
    + Elim      (2:2): x1.2 (enough for 1 more resup, ~60N)
    + Deep Scan (2:1): x1.2 (enough for 1 more resup, ~60N)
    + Sabotage  (1:2): x1.35 (slightly over 2 resups, > 120N)
    + Sabotage  (2:2): x1.1 (just enough for 1 more resup, ~60N)
    + PE        (3:2): x0.834 (reduced ~ 1 resupply, 60N)
    + PE        (3:3): x0.878 (reduced ~ 1 resupply, 60N)
- Added NitraMultiplier for Deep Dive Secondaries with approximate values: 
    + 1 Extra resupply (~60N) on Eggs, Dreadnought Cocoon and Black Box.
    + 0.4 Extra resupply (~25N) on Deep Scan and Morkite Well.
    + Unchanged in Mini-Mules and Morkite. For Mini-Mules secondaries, Nitra Reward from Reparing is reduced from 50 -> 30 Nitra, but Scanning and Repair Time are reduced by -33.3%. Unaffected in Salvage mission type.
    + Side Note: This value is also compatible with current Main objective if they have nitra multiplier support, calculated additively.
- Disabled player headbounces.
- Banned most gameplay changing anomaly + warnings. These that remain are Rich Atmosphere, Critical Weakness, Cave Leech Cluster, Parasites and Swarmageddon.

# Enemies
- Swarmer
  + They are now stunnable.
  + Base HP 12 -> 5.
- Sentinel
  + They are the bugs the Dreadnought Hiveguard summon. Electric Weakness +30%.
  + They also move +25% faster.
- Leech
  + They grab and damage +100% faster.
  + However, if a Leech from high up grabs you and it's killed, you will not die of fall damage.
- Fat Leech (CD2)
  + They are CD2-modified Cave Leeches that are bigger scaled and it has more HP (600 Base HP).
  + It also moves slower than normal Cave Leeches, but it has extreme horizontal range; it can grab you at a near 90-degree angle.
  + Physical Damage Multiplier +200% (Can kill them in 1 Damage-upgraded Power attack at 4p).
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
  + They now instead spawn either White Exploders or slightly rare Frost Exploders, both move -25% slower. Frost Exploders after exploding will leave Frost Bomber's Snow that slows player down and inflict Cold Damage.
  + They are rarer in Escort.
- Patrol Bot
  + They spawn globally independent of Rival Presence or Industrial Sabotage.
  + No longer do Bump Attack (You take damage and get knocked back).
- Nexus
  + They have Fire Damage Weakness +295%. 
  + They now instead spawn white Slashers that only have ~66 HP.
- White Exploder (MEV)
  + Apart from spawning from Breeders, these also spawn from Swarmer Eggs (Halved damage dealt, smaller Scaled).
  + They also move -25% slower.
- Exploder
  + They move +50% faster.
- Goo Bomber
  + They have 25% chance to promote into Acid Bomber, cannot be promoted During Encounters.
- Acid Bomber (DEA)
  + These are the promoted variant of Goo Bomber, coming from DEA. Their materials are changed slightly.
  + Bombing attack now drops goo that have the properties of both sentinel goo and septic spreader goo.
  + Their normal projectile attack will leave rockpox goo texture behind when dodged, does a 50/50 split of poison/explosive damage rather than explosive, and applies the acid spitter STE if it hits you.
  (Description mostly copied from von's website)
- Septic Spreader
  + They have 25% chance to promote into Ice Spreader.
- Ice Spreader (CD2)
  + They are the promoted variant of Septic Spreader. Their materials are changed also.
  + The projectile is now a Snowball projectile, which deals high Cold Damage to player that has damage high drop off over further distance. It will instantly freeze player at Direct or Close hit.
  + There can only be a certain number of Ice Spreaders available on-field.
- Grabber
  + They spawn spread out from waves. There is 30% chance to promote into Deliverer and 25% chance (Lower chance in lower player count) to promote into Carrier instead. If carrier is Banned in certain scenarios, Deliverer promotion chance is now 33.3%.
  + They move +50% faster.
- Deliverer (CD2)
  + They move -30% slower and have Fear immunity. Their materials are changed slightly.
  + They won't flee away or drop you down after taking damage.
- Carrier (CD2)
  + They are Elite Grabbers that have Base HP -50%, and move +50% faster than normal Elite Grabber.
  + Grab Time is reduced to 10s.
  + They are banned During Encounters, Defense, Drillevator, and in 1p.
  + There can only be a small number of Carrier available on-field.
- Bulk Detonator
  + They move +50% faster. 
  + They also tend to spawn far from the team. On an Escort, they spawn at a normal distance from the team.
- Ice Detonator (MEV)
  + They move +50% faster, and is slightly rarer than Bulk Detonator.
  + Stomp and Explosion damage type changed to Cold damage, which will instantly freeze you.
  + Leave no Meetball on Explosion but have a larger damage range and blast player away.
- Sonic Detonator (CD2)
  + It's a rare bulk variant that has Base HP x0.25.
  + Instead they move +100% faster than normally with Time Dilation +35% and significantly higher turning speed.
  + They tend to spawn moderate distance from the team.
  + On death, its explosion and carve radius are slightly reduced but shoots 16 Meatballs instead of 8.
  + It cannot be spawned During Defense, Drillevator and Escort. 
- Flying Rock from Heartstone phase
  + Base HP 250 -> 90/120/148 (same Base HP as Grunt/Acid Spitter/Slasher).
- Trawler
  + They spawn globally in all biomes. But only via Wave Spawner.
  + They have Time Dilation -25%.
  + Maximum spawn on field reduced to 0/2/4/5 before Wave Spawner is disabled.
  + Wave Spawner is disabled in 1p by Default.
- Oppressor
  + They move +100% faster. 
  + Maximum spawn on field reduced to 2, and 1 during Defense, Hacking and Escort Moving phase. At 1/2p, this number in both scenarios is reduced by 1.
- Stalker (Beta Stalkers from MEV)
  + They are replaced with their Beta version. 
  + Set your Effects in the in-game options to High to see them while they are cloaked. If you have Low Graphic Stalker Fix mod then you can ignore this line.
  + No longer spawns in Solo.
- Naedocyte Seeder (CD2)
  + It's a rarer Breeder that is bigger sized and only spawns in a wave (Highlighted by Enemy Outline, disappear after being pinged by player and expire). Their materials are changed also.
  + Base HP & movement speed -66.66%.
  + They now instead spawn smaller and different look Sentinels that inherit every trait of normal Sentinel (Except bonus movement speed), with some extra stats: Fire damage resistance +25%, Base HP -40%, and Damage Dealt -25%.
  + It will bleed out (lose HP) after 2 minutes of being in the map and dies exactly 2 minutes later (The timer value is lower in player count).
- Naedocyte Thugger (CD2)
  + It's another rarer Breeder that is bigger sized and only spawns in a wave (Highlighted by Enemy Outline, disappear after being pinged by player and expire). Their materials are changed also and is different than Seeder. 
  + Base HP & movement speed -66.66%.
  + They now instead spawn swarmer sized with different look Oppressors named "Glyphid Thug" that move slower than normal Oppressor, have Base HP x0.05 (5% HP), Damage Dealt -35% and have no hitbox collision. On death they leave behind Frost Praetorian's gas instead. They also die to normal pickaxe hit.
  + It will bleed out (lose HP) after 2 minutes of being in the map and dies exactly 2 minutes later (The timer value is lower in player count).
- Battle Blimp (CD2)
  + It's another rarer Breeder but different variant that only spawns in a wave. Their materials are changed also and scaling is bigger.
  + Base HP +100%, Freezing temperature is increased to -400c and It spawns Patrol Bot's homing missile projectiles in short interval.
  + On death or Frozen, it will spawn 6-13 red crawlers (Scale with player count) named "Airship Crewmate" with different material to attack your team. They have Base HP +25% and slightly higher Damage Dealt.
- Elite Guard, Elite Grunt Slasher, Elite Mactera Spawn, Elite Septic Spreader, Elite Ratter and Elite Stingtail (CD2 - DEA)
  They spawn globally independent of Elite Threat, and mostly spawn via custom Wave Spawner. Individual changes are below: 
  - All Elite enemies except Guard have material change (to tell them if they are weak).
  - Elite Slasher: Has 265/274/309/336 HP (based on Crawler Normal Scaling at 4p).
  - Elite Ratter (DEA):
    + They are ground Acid Spitter that lob a projectile that spawns 1 Glyphid Rat (Detail below)
    + Has 140/145/164/177.6 HP (based on Slasher Normal Scaling at 4p).
    + Additionally, movement Speed now +50%.
  - Elite Septic: Has 114/117/133/144 HP (based on Acid Spitter Normal Scaling at 4p). Additionally, Time Dilation +30% and Damage Dealt -20%.
  - Elite Mactera Spawn: Has 95/98/110/120 HP (based on Cave Leech Normal Scaling at 4p). Additionally, Time Dilation -15% and Damage Dealt -10%.
  - Elite Stingtail: Has 211/218/246/267.6 HP (based on Mactera Spawn Normal Scaling at 4p). Additionally, move +40% faster and gain +20% Physical Damage weakness.
  - Elite Guard: Has 967/999/1128/1225 HP (based on Menace Special Scaling at 4p). THEY ONLY SPAWN IN WAVES.
- Glyphid Rat: 
  + They are bigger sized Swarmer that won't die when ignited/frozen. Their materials are changed also.
  + Base HP 12 -> 20, move +20% faster and Damage Dealt +50% than normal Swarmer.
  + There are variants that spawn only on swarmer tunnel and glyphid egg, they are named as Glyphid Sewer/Hatched Rat, have Base HP 12 -> 50 instead, 50% resistance to Fire Damage and Fear Immunity. They also have Different base materials.
- Mactera Plague Bomber (DEA)
  + These are Goo Bomber variant that have Base HP -25%. Their materials are changed also.
  + Normal attack projectile is now replaced with Glyphid Dreadnought's Eggshot projectile that spawns a bunch of Glyphid Rats and apply Pheromone STE.
  + Bombing attack now spawns individual Glyphid Rats instead.
  + On its presence, all Glyphid Rats on-field gain +60% Damage Resistance (Reflected by Blacker material change). This buff is removed when all on-field Plague Bombers are dead.
- Glyphid Dreadnought (BOSS)
  + Glyphid Dreadnought's Eggshot projectile spawns a bunch of Glyphid Rats instead with Pheromone STE.
- Turbo Menace (MEV)
  + They are flashy Menaces from MEV that have Base HP 800 -> 100.
  + Instead, they shoot a laserbeam of projectiles.
- Fanatic (DEA)
  + They are another Menace variant from DEA that have Base HP 800 -> 100 and Slower shooting AI than normal Menace.  
  + Instead, they fire the Arbalest Fireball Fan attack.
- Glyphid Architect (CD2)
  + It is a rare menace variant that has Base HP x0.7855 and Time Dilation -25%. Its material is changed also.
  + Normal projectile is now the default (No Upgrade) Engineer's Platform. Its purpose is to disrupt surrounding terrain around players.
- Lacerator + Arbalest (DEA)
  + They can spawn in waves that have Base HP of 600 (Brundle's). 
  + They will not try to heal with each other so burrow and fireballs pan attacks are locked.
  + Both have 20% chance to promote into Wallhacker and Banshee respectively, cannot be promoted into these variants during Defense and Drillevator.
  + Arbalest cannot be spawned during Drillevator in 1p setting.
- Wrathbane + Banshee (CD2, DEA)
  + These are the promoted variant of twins. They retain all stats from weak twins previously and have different materials.
  + Wrathbane: Damage Dealt -65%. Wrathbane is a type of Lacerator that has Stomping rockwall projectile replaced with Scorching Tide projectile (Has limited range, deadly in close range, low ground attack) and Flaming Breath attack replaced with Burrow.
  + Banshee is a type of Arbalest that only uses Grieves attack.
- Youngnought and Ice Youngnought (DEA)
  + Both are a type of weak Glyphid Dreadnought which have Base HP of 1000, can be ignited by default and the weakpoint is opened at all time. Youngnought can spawn in waves, but can be promoted into Ice variant with 25% chance. Ice Youngnought has slightly altered appearance. Fun fact: Youngnought = Youngling Dreadnought shortened. 
  + Youngnought abilities: Fireball attack, Slam attack (Have signifcantly higher damage drop off) and Eggshot attack that spawns a bunch of Grunt variant that are named as Streakers. They have Base HP of 148 HP (Slasher's), move faster than normal Grunt but have no armor and retain most swarmer moveset.
  + Ice Youngnought abilities: Snowball attack, Ice Slam attack that deals Cold Damge instead (Mostly freeze you, have signifcantly higher damage drop off) and Eggshot attack that spawns a bunch of Ebonite Grunt (It's resistance is normal grunt) that are named as Moles. They have Base HP of 148 HP (Slasher's), and they can do the Lacerator's Burrow attack that deals normal damage with no knockback. Their materials are slightly changed. Ice Youngnought on death will leave behind Frost Praetorian's gas.
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
- Big Bulk Detonator (MEV)
  + This is a very rare Big Bulk Detonator from MEV that have its material changed.
  + It has Base HP +50% of Normal Bulk (4000 -> 6000).
  + It also has massive Electric damage weakness, large Corrosion damage Weakness and Piercing Damage Resistance. 
  + On death, it leaves behind significantly larger explosion and carve radius. The carve material is changed into Hot rock from Magma Core terrain. 
  + It cannot be spawned during Defense, Escort mission type and 1p setting. Once spawned it has a massive cooldown timer before it can return into EnemyPool, and can only be spawned once in small 1-room mission type.
- Brundle
  + They have 30% chance to promote into Brendle.
- Brendle (DEA)
  + They are the promoted Brundle variant from DEA.
  + They shoot fast Breach Cutter projectile that pierce through and deal high damage to player.
- Bundle (CD2)
  + They are another Brundle variant that is bigger scaled. Their materials are changed also.
  + They deal normal damage but have the Base HP of 600 -> 800 (Goo Bomber's).
- Big Shredder (CD2)
  + They spawn in a pair. Base HP x12.82, Damage Dealt +100% and is immune to Fear.
  + They don't have any weaknesses of small shredders.
- Shredders
  - Can now spawn in every mission types. They have way higher rarity now since Big Shredder can also spawn along side Shredders. Banned in 1p setting.
- Vomit Spitter (CD2, DEA)
  + They are ground Web Spitter that spit Barrager's vomit projectile in an arc. Their materials is changed also.
  + Use Acid Spitter's AI, mean that they will aggressively shoot at you once they stop moving.
  + They have improved accuracy compare to Astral difficulty's version.
- Barrier Shooter (CD2)
  + They are Acid Spitter that spit Nemesis's barrier. Their materials is changed also.
  + Use Web Spitter's AI, mean that they will reposition after shootting once.
  + They move +50% faster.
- Barrinator (CD2, MEV)
  + This is a rare Bulk Detonator from MEV that have its material changed.
  + It has Base HP x0.175 (Around 1000 HP) and move 50% faster than normally.
  + On death, it leaves a normal bulk crater, but it shoots out 6-15 Eggshot projectiles (Scale with player count) that each turn into 2 Barrier Shooters that have additional Damage Dealt +20% stats.
- Kamikaze Goo Bomber (CD2, DEA)
  + They are another Goo Bomber variant. That is very small ascaled, and glows (Material change).
  + Their have about the health of a Swarmer and do not attack normally.
  + Their main objective is to die on top of the team and leave behind goo everywhere.
- Crawler
  + These can spawn in waves globally independent of the Core Stone event.
- Barrage Infector
  + These are rarer than usual and are even rarer on Escort.
- Tower of Babel (CD2, DEA)
  + They are Giant sized burst turret that have no base Turret attached (from DEA). Their material are also changed.
  + Stationary unit.
  + They have Base HP of 1500 (Higher than Barrager, to compensate for higher Weakpoint bonus damage). And significantly lower Freeze temperature, and moderately lower Burning temperature. Damage Dealt x0.125.
  + They have longer lock-on time than usual, but the projectile they shoot is a burst of triple Scorching Tide projectiles. 
  + It cannot be spawned on Escort mission type.
- Nuke Barrager (CD2, DEA)
  + They are more expensive Barragers that have Time Dilation -66.66% (Even slower Time Dilation when spawned in the first 20s into the Mission). Their materials is changed also.
  + Stationary unit.
  + Projectiles they shoot are low velocity Fat Boy nukes that instakill anyone in the blast radius and leave behind a cloud of radiation.
  + The projectiles WILL carve terrain and CANNOT be shot down.
  + Only one can spawn in Refinery and Escort. In 1p setting, this applies for every mission types.
- Scalebramble (CD2)
  + They are rarer than usual. Only one can spawn on Escort. They are time dilated to half speed.
- Warden Bomber (MEV)
  + They are pink Goo Bombers from MEV.
  + Once alerted, they spawn 8 Mactera Spawns. 
  + Any mactera type enemies that are close to Warden Bomber can be healed and gain damage resistance similarly to Glyphid Warden.
  + It does not attack normally. On death it won't drop goo.
- Pentajaw (DEA)
  + They are Trijaws from DEA that shoot two additional projectiles. 
  + They are veteran of a Trijaw and follows VeteranLarge promotion (30%).
- Mactera Solaris (DEA, CD2)
  + It's a modified Radial Jaw (Trijaw variant) from DEA that becomes a mini boss variant. Its material is slightly changed also.
  + It has significantly higher HP than normal Trijaw, TimeDilation +150% and higher movement speed.
  + It has high elemental, explosion damage resistances (Except for Physical damage where it's weak instead). It also has a very high stun resistance, very long stun cooldown after being stunned once and extremely high Freezing temperature (-400).
  + Its attack drops A LOT of low velocity BET-C bombs in circular pattern that deal similar damage as being hit directly by Glyphid Dreadnought's Fireball.
  + It cannot be spawned during Defense, Drillevator and Escort Heartstone phases.
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
- Big Youngling (CD2)
  + They are bigger sized Youngling that have more HP than original version (Stingtail's Normal Scaling at 4p, lower health at lower player count).
- Glyphid Tarantula and Glyphid Juvenile (CD2)
  + They are another Glyphid Warden variant with different quirk.
  + Their Base HP -50%, no longer buff any Glyphid enemy.
  + Instead, upon alerted, other than spawning a bunch of Grunts, it also spawns a burst of Glyphid Juveniles, then after that few Juveniles will be spawned periodically.
  + Glyphid Juveniles are another web spitter variant that move +50% faster, and spit Menace projectile with same damage as Web Spitter with Electric STE. After shooting, they will reposition for next shot.
  + Both Tarantula and Juvenile have different look (materials changed).
- Glyphid Spy (CD2)
  + They are another Web Spitter variant that is swarmer sized, and have their look changed into Season 5 stalker material (barely visible).
  + They have Base HP 40 -> 90 and Move extremely fast.
  + They have extremely high Fire, Cold, Electric, Corrosive and Explosive damage resistances, cannot be ignited, frozen and stunned.
  + The projectile is Breach Cutter projectile with either fast or slow moving speed that deals moderate damage to player. After shooting, they will reposition for next shot.
- Q'ronar Ninja (CD2, MEV)
  + They are Shellback variant that are smaller scaled and spawn far away from the team. Their materials are changed also.
  + Base HP is the same as Tri-jaw Normal Scaling At 4p, so lower player count gets lower HP. 
  + Damage taken stats: Electricity x1.2, Physical x2 (Weak) and Fire x1.
  + Their AI have been tweaked to have instant walking speed (Teleport) and rarely roll around. Which mean they will do more spit attack than Shellback normally.
  + They do only x0.15 contact damage (No knockback and damage RNG) with slightly lower range when they roll. Their projectile is fused with Electricity STE, but their damage dealt -67%.
- Mactera Joker (CD2, MEV)
  + It's a mini boss Mactera Spawn variant that has material changed.
  + It has significantly higher HP than normal mactera spawn, Time Dilation +50% and dash slightly faster than normally. The projectile has long Poison DoT STE appliance and different trajectory visual effect than normal Spawn.
  + It also has high elemental, explosion and piercing resistances (Except for Physical damage where it's weak instead).
  + Its main ability is to Summons clones of itself named Mactera Joker Clone on the map once Spawned with no HP bar indicator and a slight difference on its appearance.
  + The clones inherit Time-Dilation trait from the real Joker, but have significantly higher dash speed, lower HP and no resistances. 
  + The clones can instantly respawn upon being defeated and only deals 1/3 of real Joker damage and without Poison DoT STE.
  + Upon killing the real Joker, all clones will instantly die.
  + Both real and clone Jokers have high Stun resistance, long stun cooldown after being stunned. Joker has higher Freezing temperature (-320). Clones after being Frozen will respawn back after short delay. 
  + Joker cannot be spawned during Defense and Drillevator.
 

# Custom Waves
- During a Dreadnought fight (OG Dreadnought, Hiveguard, normal Twins), a Bulk Detonator known as a "DreadHelper" with Base HP x0.85 will spawn in to allow the team to kill the Dreadnought faster (Highlighted by Item Outline, disappear after being pinged by player and expire). Only one DreadHelper can exist at a given time.
- During a Caretaker fight, a Weak Bulk Detonator known as a "CaretakerHelper" with slower movement speed and Base HP x0.25 will spawn in to allow the team to speed up Caretaker fight (Highlighted by Item Outline, disappear after being pinged by player and expire). It has halved carve radius compare to Normal Bulk. Only one CaretakerHelper can exist at a given time. Its material is slightly changed to distinct from Bulks that spawn from Waves.
- During Dreadnought or Caretaker fight, Normal Wave will spawn in periodically. For Dreadnought fight, the Interval is increased by 50, but the beginning of the fight will guarantee a Normal Wave spawn.
- Every 60 seconds (Longer during certain pressure scenarios), either 20 Grunts with 1-4 White Spitters (Web Spitter but have no Web STE on attack), a Bundle or/with 2-3 Mactera Spawns, or 2-3 Mini-Bulks spawn. The chance they spawn is split into 67%/21%/12%. Mini-Bulks from this WaveController are not allowed to spawn on Escort, and disabled during Defensive objective and Drillevator.
- Every 90 seconds, a Trawler spawns. This wave controller is disabled in 1 player count lobby. Up to 0/2/4/5 trawlers can be available in the map.
- Every 45 seconds (Longer during certain pressure scenarios), a mix of 2-4 weak Elite enemies will appear. The pool are: 1-2 Mactera Spawns, 1-3 Slashers, 1-2 Septic Spreaders, 1 Stingtail and 1-3 Ratters. Elite Stingtail is not allowed to spawn in 1p, otherwise they have a moderate cooldown timer after they spawned. Elite Septic is not allowed to spawn in 1p during Drillevator, otherwise in same scenario, they have a moderate cooldown timer after they spawned. This wave spawner will be paused when a downed player is detected.
- Every 110 seconds (Higher during Escort Heartstone phase), a Penta-jaw will appear.

# Miscellaneous:
- Bandaid bug fix: Darkness module somehow caused scout's flare gun to have significantly less duration time so I added FlareGunDuration field value in Darkness module file, so it matches 90s of duration (1 duration upgrade) most scout upgrade path will take.
