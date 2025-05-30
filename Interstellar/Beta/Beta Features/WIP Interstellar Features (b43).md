As Interstellar is still a WIP difficulty, this feature list may be subject to change. This list is updated to b43 version.
This difficulty used FC_b23 - a difficulty made by pH-JPEG, as a framework, but with adjustments. As a result, this feature list might repeat some lines with same description as FC_b23.

# General (Mostly the same as FC)
- Enemy HP scaling follows Hazard 6.
- Enemy movement speed follows Hazard 7.
- Enemy damage scaling follows Hazard 7.
- Initial resupply cost is 40 nitra, afterwards it raises to 60 nitra (50 nitra instead for 1/2p setting).
- Enemy projectile speed follows Hazard 6 and Hazard 7.
- Friendly fire is set to 110%.
- You revive with 40% HP and regen up to 40% of your HP compared to the typical 10% seen in Hazard 5 and other modded Hazards. You begin to regenerate your HP after 6 seconds if you don't take any damage. It takes 10 seconds to regenerate from 1 HP to 40% HP once the regeneration begins.
- Dorretta resists 75% of damage; it is the same as the value used in 6x2.
- During the Extraction phase of a mission or the PE countdown until the Drop Pod lands, x1.66 or x2 more bugs spawn respectively.
- During the time in-between the Fuel Cells and the Drop Pod opening on a Salvage mission, there will initially be a pause in bug spawns with the amount of bugs spawning greatly increasing as the Drop Pod gets closer to opening.
- Whenever an Egg is pulled, if it does not trigger a swarm, the wave it summons spawns x4 the bugs.
- Wave timers are loosely based off of Hazard 7 with low chances for a swarm to spawn instantly, only in Refinery mission type. This wave timer distribution is a slightly on easier side compare to FC.
- A "fat" wave of bugs can occasionally spawn. This is a wave that is twice the size of a typical wave. The chance for "fat" wave was nerfed compare to FC
- Enemy diversity is higher and more variable; this means you can get multiple types of enemies all spawning at once with the amount being variable. You could get a superdiverse wave or a wave of only one or two enemy types.
- Most caves will have at least one of every Stationary type if possible.
- Veteran chance has been significantly increased; this means more Guards, Slashers, Brundles, Trijaws, and Oppressors. Some of the enemies can also be promoted into new type of enemies, with own's custom veterans chance.
- Many new enemies have been added in the form of enemies that normally don't spawn in waves and entirely new enemies from CD2, MEV and DEA.
- Some existing enemies have been modified.
- Custom waves of certain enemies spawn at set intervals or conditions.
- (new) Adjusted mission types enemycount mostly to be more balanced, harder in Encounters & Pressure waves in Point Extraction, Refinery refining phase, Drillevator and Uplink/Refuel/Blackbox. Slightly easier on Escort Final phase 1 and 2, any phase before Hacking and Caretaker phase in Sabotage, and normal and pressure wave of Deep Scan. Significantly easier in Refinery Stalling/Reparing phase.
- (new) During the time of Uplink/Refuel/Blackbox objectives, penalty of draining the progress bar is reduced by 30% (50% on 1p setting), and Mission Control will no longer shout at you with "Get back to the triangulation zone! We're losing you" type of quotes if you no one is at triangulation zone.
- (new) Disabled player headbounces.
- (new) Breeder type enemies (except for Battle Blimp) have lowered Freeze temp.
- (new) Patrol Bot enemies have lower freeze temp. Rival Turrets spawn count in Encounters sabotage mission type is reduced by 50%.
- (new) Added x1.2 NitraMultiplier on specific mission type (Length:Complexity) Mining 2:1, DeepScan 1:2, and Sabotage 2:2. Sabotage 2:1, Elimination 2:2, Elimination 3:3 gains x1.55/x1.35/x1.1 instead. The reason behind this is these specific mission type has significantly way lower Nitra generation than the only slightly longer or bigger missions, which can cause Attrition issue very fast (especially in sabotage with stationary and swarm).
- (new) Lower player scaling will have some change to the existing enemies to make playing easier, especially in 1-2p setting. Such as: Increase Player Light Intensity by 50% (25% if 3-4p setting) if Scout doesn't present. Barrager type enemies MaxSpawnCount reduced to 0, and they gain signficantly less SpawnAmountModifier than before, (1p setting only) their HP stats is reduced to be the same as Spitballer's and gain 100% weakness to fire like Spitballer. Bulk type enemies are banned during 1p defensive objective. Shockers have added NoSpawnWithin in 1/2p setting, and have spawncount significantly reduced in 1p setting. Escort during Heartstone phase on 1p setting, Doretta gains +40% resistance. 
- (new) Added NitraMultiplier for Deep Dive Secondary with values: +25% on Eggs, +20% on Black Box and Dread Cocoon, +10% on Deep Scan and Morkite Well, unchanged in Mini-Mules and Morkite. This value is also compatible with current Main objective if they have nitra multiplier support, calculated multiplicatively.
- (new) Added Elimination and Caretaker with wave functionality (via Wave Spawner), so now you can uninstall Elim and Caretaker with waves mod since we have them in my difficulty with better balance.
 
# Enemies
- Swarmer
  - They are now stunnable, and Base HP reduced 12 -> 5.
- Sentinel
  - These are the bugs the Dreadnought Hiveguard summon. These also move 25% faster and have Electric weakness by 30%.
- Leech
  - These move x2 faster, if 1p setting then only x1.5 faster. However, if a Leech from high up grabs you and it's killed, you will not die of fall damage.
- Fire Bomber
  - This is an unused enemy in the game files. It behaves like a normal Goo Bomber, except it drops bomblets that deal extreme damage to players.
- Acid Spitter
  - These deal -20% less damage, slightly changed material and have rarity increased in 1/2p setting.
- Breeder
  - These take x2 damage. A Breeder can sometimes respawn in a wave. Both natural and respawning Breeders also spawn white Exploders from MEV that move at x0.75 speed. White Exploders spawned from Breeders have a 35% chance to promote into Ice Exploder.
- Patrol Bot
  - These spawn globally independent of Rival Presence or Industrial Sabotage. Damage taken is increased to x3 when being Frozen. SpawnCount is scaled with Player Count.
- Nexus
  - These take x3.95 fire damage. They also spawn white Slashers from MEV that only have 66 HP.
- Sentinel Swarmer (MEV)
  - These are small, blue Sentinels from MEV with little HP. They still leave goo upon death. They can only spawn from Swarmer Tunnels.
- White Exploder (MEV)
  - Apart from spawning from Breeders, these also spawn from Swarmer Eggs. These also move at x0.75 speed.
- *new* Ice Exploder (MEV)
  - These are the MEV Exploder, come from the promotion of Breeder White Exploder that will leave behind Ice Bomber's bombing snow after it explodes. 
- Exploder
  - These move x1.5 faster.
- Septic Spreader
  - They have 17.5% chance to promote into Ice Spreader in 2p+ setting. There can only exist 1/2/2/3 Ice Spreaders in 1/2/3/4p setting. 
- *new** Ice Spreader (CD2)
  - They are the promoted variant of Septic Spreader which lobs Snowball projectile at your team, direct or close aoe zone hit will instantly freeze the player, but the damage will drop off on further distance. Its look is modified via CD2.
- Grabber
  - These move x1.5 faster, in 1p lobby it's only x1.25 faster instead. They have 35% chance to promote into Deliverer, and 6.25%, 18%, 30% promotion chance in 2p/3p/4p to promote into Carrier respectively. If Carrier is banned in certain scenario, the chance to promote into Deliverer is now 50% instead.
- *new* Deliverer (CD2)
  - This is a promoted type of grabber that has 20% more HP than normal Grabber and 30% slower time dilated, 41.75% slower timedilated if 1p. Instead they have fear immunity, and won't flee away or drop you down once you're grabbed. Its look is the same as normal grabber, only name change.
- *new* Carrier (CD2 - inspiration from DH difficulty)
  - This is an elite version of promoted type of grabber that has only 35% of original elite grabber's HP. Instead they move extremely fast and only have 5s of Grab Time. It's banned in Defensive objective, Drillevator, additionally in Encounters and as well as in 1 player count lobby. Ignition and Frozen temp is the same as normal Grabber (30c and -150c).
- Bulk Detonator
  - These move x1.5 faster. They also tend to spawn far from the team. On an Escort, they spawn at a normal distance from the team.
- *new* Ice Detonator (MEV)
  - These are the MEV Bulk type that move x1.5 faster, spawn far from the team and its attack and explosion will cause freeze damage instead. Explosion leaves no meatball but it will blast players away if they are caught within the explosion zone. Explosion size is reduced by 33.33%. It's weakpoint is changed and now glow in the dark via CD2.
- *new* Sonic Detonator (CD2)
  - These are another type of Bulk which have oppressor's base HP (900HP). Freeze and Unfreeze temp is now only -240 & -100, and they warm slower than normal bulk. They move at more than x2 movement speed, 180 degrees turning speed and its explosion will spawn 16 meatballs instead of 8.
  It's explosion damage radius and max damage radius is reduced by 20%. It's banned in Defensive Objective, in Drillevator and Escort. 
- Flying Rock from Heartstone phase
  - Reduced Base HP from 250 to 90/120/148 (same Base HP as Grunt/Acid Spitter/Slasher) in 1/2/3p+ setting.
- Trawler, *new* Glacial Praetorian, Glacial Bomber
  - These spawn globally in all biomes. Trawler won't spawn normally in the pool anymore but via wavespawner instead. Trawler has 25% less time dilation than normally.
- Oppressor
  - These move at x2 speed, x1.5 speed if 1p setting. If 2 or more Oppressors are present on the map, no more Oppressors will spawn in, this number is decreased to 1 on 1/2p setting. During the Uplink/Fuel Cells/Black Box/Hacking, 0 Oppressor will spawn in 1/2p setting. For other players setting, if 1 or more Oppressors are present on the map during the Uplink/Fuel Cells/Black Box, no more Oppressors will spawn in. 
- Stalker (Beta Stalkers)
  - These are replaced with their Beta version. Set your Effects in the in-game options to High to see them while they are cloaked. In 1/2p setting, MaxSpawnCount reduced to 0, and increase the Rarity.
- *new* Naedocyte Seeder (CD2)
  - These have a rare chance of spawning in a wave that has x2 damage taken (similar to normal breeder). These move at 1/3 of original movement speed, spawn yellow color with slightly-smaller sized Sentinel with 60% of original HP, deal 25% less damage than normal Sentinel and have 25% fire damage resistance, and 30% electric damage weakness. These sentinel are based off NDS difficulty descriptor with some tweaks. Its looks is modified by CD2. In 1p setting or Deep Scan mission type, they bleed out after 1 minute of being in the map.
- *new* Naedocyte Thugger (CD2)
  - These have a rare chance of spawning in a wave that has x2 damage taken (similar to normal breeder). These move at 1/3 of original movement speed, spawn swarmer sized Oppressor named "Glyphid Thug" with ~5% of original HP, deals 35% less damage than normally, halved freeze temperature and leave behind Glacial Praetorian's gas once died. Thugger and Thug's look is modified by CD2. In 1p setting or Deep Scan mission type, they bleed out after 1 minute of being in the map.
- *new* Battle Blimp (CD2 - from Nightmares difficulty)
  - This is a very rare bigger sized Breeder that will rapidly shoot Patrol Bot's slow missile (1 missile very near or high than 1s). It has x0.5 damage taken and upon its death, will spawn 7-14 crawlers named "Airship Crewmate" which have 25% more HP, deal 10% more damage to attack your team (scaled with playercount). Blimp and Crawlers' look are modified by CD2. There can be only 1 Blimp spawn in the map.
- Elite Guard, Elite Grunt Slasher, Elite Mactera Spawn, *new* Elite Septic Spreader, Elite Stingtail and Elite Ratter (CD2 - DEA)
  - These spawn globally independent of Elite Threat. All (except for Guard which is in normal pool instead) spawns from wave spawner, with its look modified and are slightly bigger sized. Further changes are as below:
  - All have lower burning and freezing temperature compare to vanilla elite enemies, but the number is still higher or equal to normal enemy type.
  - Elite Guard gains x1.396 damage taken increase. They ONLY spawn in normal waves. Its look is default.
  - Elite Mactera Spawn gains x10.088 damage taken increase. They are also 15% slower time dialated and deal 10% less damage.
  - Elite Slasher takes x3.2 more damage than usual.
  - Elite Septic Spreaders have the HP of a normal grunt, are 30% faster time dilated and deal 20% less damage.
  - Elite Stingtails have the HP of a normal grunt, and move x1.4 faster.
  - Elite Ratter (DEA) is a ground acid spitter that have the HP of a normal grunt, and will lob a spawner projectile that spawn 1 Glyphid Rat, which is a modified bigger look swarmer that move x1.2 faster, has a HP of an exploder and deal x1.1 of damage normally (they deal x1.3 more damage instead if atleast 1 Plague Bomber presents in the map). They also don't die from being on fire and frozen.
- *new* Mactera Plague Bomber (DEA)
  - These are the Bomber type that shoot out pheromone STE on single target attack, and its bombing will spawn Glyphid Rat. On its presence, every Glyphid Rat in the map will gain 71.5% damage receive down, and ~18% damage dealt up. reflected via a different Glyphid Rat's material look. This buff and material look will be reverted back once no more Plague Bomber is presenting in the map.
- *new* Acid Bomber (DEA - from NDS difficulty)
  - This is another DEA Bomber variant which drops goo with properties of both sentinel goo and septic spreader goo. Its projectile attack will also leave rockpox goo texture behind when dodged, does a 50/50 split of poison/explosive damage rather than explosive, and applies the acid spitter STE if it hits you (mostly copied from von's website). Its look is changed via CD2.
- Turbo Menace (MEV)
  - This is a flashy Menace from MEV. It shoots a laserbeam of projectiles, but it only has 100 HP, giving it slightly less than a Grunt.
- *new* Glyphid Architect (CD2)
  - This is a yellow aura colored menace that has the base HP of a vanilla Korlok Sprout and shoots Engineer's platform rapidly with 25% slower time dilation. Its look is heavily modified by CD2. There can only be 1 or 2 Architect in the map and can only spawn 1 Architect at a time in 1/2p setting.
- *new* Lacerator + Arbalest (DEA)
  - These can spawn in waves. Both have Brundle HP. They will not try to heal with each other. Both have a 20% promote chance to become Wallhacker and Banshee respectively, cannot be promoted into these variant during Defensive Objective.
- *new* Wrathbane + Banshee (DEA)
  - These are the promoted version of twins. Both have Brundle HP. Wrathbane is a type of Lacerator that deals only 25% of damage, instead it has its stomp's rockwall projectile replaced with Scorching Tide projectile (Has limited range, deadly in close range, low ground attack) and Flaming Breath attack replaced with Burrow. Banshee is a type of Arbalest that only uses Grieves attack. They also have different look via CD2.
- *new* Youngnought and Ice Youngnought (DEA - from NDS and LX Revamp difficulties)
  - Youngnought can spawn in waves, but can be promoted into Ice Youngnought with 25% chance. Both are the weak OG Dreadnaught variants which have significantly less HP than the original variant. Youngnought has the OG Fireball, Slam (with even more damage fall off on distance) and Egg Shot that spawns 1 Glyphid Rat (lol). Ice Youngnought has the Snowball, OG Dread Slam attacks with Cold Damage and Egg drop that spawns Grunt Mole with Ebonite mesh (white texture also), 148 HP (Slasher HP) and a burrow attack (no knockback, deal normal grunt damage). On death they leave behind frost mist from Frost Praetorian. They are banned in 1p setting during Defensive Objective, and its cooldown is significantly longer during Defensive Objective, scales with player count (at 4p the cooldown value is doubled than normal scenario). Ice Youngnought has modified looks from CD2 and freeze temperature is slightly higher than other weak Dreadnought variants. 
- Mini Bulk Detonator (MEV). 
  - A small Bulk Detonator from MEV. Its stomp radius and explosion radius is significantly smaller than a normal Bulk's. It also shoots out less meatballs upon death. It leaves behind dirt when it dies. This also has less HP than a normal Bulk, Freeze and Unfreeze temp is now only -240 & -100, and they warm slower than normal bulk.
- *new* Line-Cutting Turret (CD2)
  - These are the modified bigger-sized Repulsion turret via CD2, made into every mission type and spawn as Stationary unit. It has the same HP as repulsion turret (600 HP) which is 50% faster time dilated and shoots Line-Cutting projectiles from OMEN Tower (damage reduced down to 70%) in many direction upon alerted. It's also immune to dying after being on fire, has freezing temperature of -200 celcius and take x3 more damage once frozen. It's banned in Escort due to its fast frequency and many lines on lazer beam which can deal ridiculous damage to Dotty. 
- *new* Rocket Turret (CD2, MEV)
  - These are the bigger sized Sniper Turret from Sabotage mission made into every mission type and spawn as Stationary unit. They are 50% faster time dilated and shoot a fast moving Patrol Bot's missile projectile that deal moderate damage to the player (the projectile deals 10% more damage normally). They can also be frozen at -100 celcius and take x3 more damage once frozen. Their looks is changed via CD2 and glow in the dark.
- Korlok Sprouts (MEV)
  - Added from MEV, Sprouts spawn as Stationaries similar to Nexuses, Leeches, Breeders, and Spitballers. These can spawn only on the ground and start off sleeping until they take damage. These take x1.2 damage.
- Nukeballer (MEV)
  - Added from MEV, this is a Spitballer that shoots a slow-moving nuke that instakills anyone in the blast radius and leaves behind a cloud of radiation. It does not carve terrain. The projectile can be shot down.
- *new* Spitscreener (CD2, MEV)
  - These are the modified look of normal Spitballer, have slower time dilated by -33.3% (50% if on 1p setting). They spawn as Stationary unit which shoot three Nemesis's barrier in each shot toward your team. Made to be rarer than normal Spitballer and possibly Nukeballer. They spawn even less in pack in 1p setting.
- Big Bulk Detonator (MEV)
  - Added from MEV, this is a super rare big Bulk Detonator that has its looks modified by CD2. It has more HP and has a significantly larger death explosion and carve radius. It leaves behind hot rock upon death. It also moves x1.35 faster. It is banned on Escort, during Uplink/Fuel Cells/Black Box events. In 1p lobby it's totally banned. It has massive Electric damage weakness, normal corrosive damage weakness and Piercing damage resistance. They have massive cooldown when spawned, and can only spawn once in small 1-room mission type.
- Brundle
  - They have 30% chance to promote into Brendle.
- *new* Brendle
  - They are the Brundle modified from DEA, which shoots fast Line Cutting projectile from OMEN Turret. Its projectile deals 10% more damage normally.
- Bundle (CD2)
  - This is a big, white Brundle possible with CD2. It deals normal damage but it has the HP of a Goo Bomber.
- Big Shredder (CD2)
  - Possible with CD2, this is just a big Shredder that spawns alone or in a pair. It deals x2 normal Shredder damage, but it has about x13 the HP of a normal Shredder. They don't have any weaknesses of small shredders, are immuned to fear and freezing temperature is reduced down to -240.
- Shredders
  - Can now spawn in every mission types. They have way higher rarity now since Big Shredder can also spawn along side Shredders. Banned in 1p setting.
- *new* Vomit Spitter (CD2, DEA)
  - These are another type of ground acid spitter which shoot low arc Barrage Infector's vomit projectile (the projectile deals 10% more damage normally). They have the base HP of a webspitter. Its look is changed via CD2. 
- *new* Barrier Spitter (CD2)
  - These are another type of web spitter which have the health of an acid spitter, being slightly bigger and move 50% faster normally. The projectile they spit is Nemesis's Barrier. Its look is changed via CD2. MaxSpawnCount is scaled with player count. 
- *new* Barrinator (CD2, MEV)
  - This is a CD2-modified Plantonator from MEV. It is as rare as the Battle Blimp. It behaves like a normal Bulk but it has only around 1000 HP. Upon death, it leaves a normal Bulk crater, but it shoots out 7/10/18 meatballs that all turn into Barrier spitter in 1/2/3p+ setting. It is banned on Escort.
- Fat Leech (CD2)
  - This is a CD2-modified Cave Leech. It's larger and it has more HP. It also moves slower than normal Cave Leeches, but it has extreme horizontal range; it can grab you at a near 90-degree angle. In 1p setting they are even more slower Time Dilated. One Damage Upgrade Power Attack can kill them full HP in 4p setting.
- Kamikaze Goo Bomber (CD2, DEA)
  - This is a CD2-modified Goo Bomber. It's very small, glows, and it has about the health of a Swarmer. Its main objective is to die on top of the team and leave behind goo everywhere. It does not have the normal shot attack of a goo bomber.
- Crawler
  - These can spawn in waves globally independent of the Core Stone event.
- Barrage Infector
  - These are rarer than usual and are even rarer on Escort.
- *new* Septic Infector (CD2)
  - These are the modified look of normal Barrager, spawn as Stationary unit, which shoot Septic lobbing shots on each projectile which deals low impact damage but leave behind big puddle of septic goo (deal poison DoT). They are more rare than normal Barrage Infector, even more so in Escort.
- *new* Nuke Barrager (CD2, DEA - from Nightmare difficulty-ish)
  - This is a rare type of Barrager that spawns as stationary unit. TIt has 75% slower time dilated in the first 90s of the mission, and 66.66% slower time dilated for the rest of the time. Every projectile it shoots is the fatboy nuke with low projectile velocity. Its look is changed via CD2.
- Scalebramble (CD2)
  - These are rarer than usual. Only one can spawn on Escort. They are time dilated to half speed. 
- Warden Bomber (MEV)
  - These are pink Goo Bombers added from MEV. These spawn 8 Mactera Spawn upon aggro and they heal them and all other types of Mactera similar to a Warden. It does not attack, it only heals.
- Fanatic (DEA)
  - This is a Menace from DEA that fires the Arbalest Fireball Fan. It has equivalent HP to a Turbo Menace (100 HP).
- Pentajaw (DEA)
  - This is a Trijaw from DEA that shoots two additional projectiles. It is a veteran of a Trijaw and follows VeteranLarge.
- *new* Mactera Solaris (DEA, CD2)
  - Mactera Solaris is a rare Mactera Radial Jaw enemy that shoots a lot of Bet-C bombs in a circular patterns that deals dread fireball tier damage, move very fast and is TimeDilated by x2.5 (at 1p setting the timedilation is x1.75 instead). It has 300-450% more HP than normal trijaw (scaled with playercount), resists against Fire, Corrosive, Explosive and Electricity damage type while being weak to Physical damage type and it's stun time is reduced to 25% compare to vanilla trijaw and they have x3 stun immunity window. Freeze temp is -400 celcius and it will die after being Frozen like any flying enemies do. There can only be 1 in the map. It's look is changed via CD2 (only the weakpoint is changed to red color). Banned in Defensive objectives and Drillevator.
- *new* The Sun (CD2)
  - Renamed from "Ommoran Rock Buffer". This is a type of ommoran flying rock. It has base HP of a Brundle, tends to spawn away or near from the team depend on mission type. On its presence, every enemy that SPAWNED AFTER Rock buffer will gain a permanent Movement Speed, Projectile Speed and Attack Speed (only grunt type enemies) buff. Killing the rock won't revert the buff on already buffed enemies. They also bleed after 30s after spawning, at 4p player setting they go to 0 HP after 30 seconds of bleeding, in lesser player count setting they will bleed faster, at 1p it's 10s after it starts to bleed. It's banned on Defensive objective, Drillevator and Escort. Its look is modified by CD2.
- *new* The Moon (CD2)
  - This is a type of ommoran flying rock. It has base HP of a Brundle, tends to spawn away or near from the team depend on mission type. On its presence, reduce all lighting strength by 75%, players' maximum health regen to 10%, revive health to 10% and unable to naturally regen your HP while The Moon is alive. They also bleed after 30s after spawning, at 4p player setting they go to 0 HP after 30 seconds of bleeding, in lesser player count setting they will bleed faster, at 1p it's 10s after it starts to bleed. It's banned on Defensive objective, Drillevator and Escort. Its look changed via CD2.
- *new* Big Youngling (CD2 - from NDS difficulty)
  - This is a bigger sized Youngling that has more HP than original version.
- *new* Glyphid Tarantula and Glyphid Juvenile (CD2)
  - These are the changed look of Glyphid Warden, they only have x0.5 HP, and won't buff to any of Glyphid enemies. Instead, they will instantly and periodically spawn Glyphid Juveniles upon Alerted and staying in the map. Glyphid Juvenile is a type of web spitter that moves at x1.5 speed and spit Electric STE Turbo Menace projectile. Tarantula still spawns Grunt upon alerted. Tarantula and Juvenile's look are changed in CD2, they have blue ice-y color scheme. Initial Spawn count, interval is nerfed in 1/2p setting. Only 1/1/2 of Tarantula can present in the map of 1/2/3+ setting (MaxSpawnCount reduced to 0/0/1 as well).
- *new* Glyphid Spy (CD2)
  - This is a swarmer sized Web spitter that has 70 Base HP, S5 Stalker's Cloak material changed from CD2, moves extremely fast and will randomly shoot either slow or fast Line Cutting projectiles from OMEN Tower at your team. It also has very high resistence to fire, cold, corrosive and explosive damage and cannot be stunned.
- *new* Ninja (CD2, MEV)
  - They are the more common yet smaller scaled Shellbacks that have different behavior. When it first spawned it will do the initial roll to you, however it's rolling won't do any collision to you, thus no damage when bumping to them. However once they start finished rolling and shooting the projectiles, they will only walk, and the walk speed is instant (Kind of like teleporting), and do the projectile attack again very quickly. They have very slightly higher base HP than a Mactera Spawn, and take x1.2 Electricity, x2 Physical and x1 Fire Damage Multiplier. Its projectile has Electric DoT fused but the overall damage dealt is reduced to 27%. Its look is changed via CD2.
- *new* Mactera Joker (CD2, MEV)
  - It's a Mactera Spawn that has special traits:
      + Is faster Time-Dilated, the attack has long Poison DoT appliance and different trajectory visual effect.
      + Has significantly more HP, elemental and piercing resistances, but they are weaker to Melee damage than normal Mactera Spawn.
      + Summons clones of itself on the map with no HP bar and a slight difference on it's appearance, they inherit Time-Dilation trait from the real Joker, but have significantly lower HP and no resistance. The clones can instantly respawn upon being defeated and only deals 1/4 of real damage and without Poison DoT.
      + Upon killing the real Joker, all clones will instantly die.
      + Both real and clone Jokers have low Stun Duration, high Stun Immunity and very high Freezing temperature (-400), because the clone won't be able to respawn back when they are frozen and die. 
  - They are banned during Uplink/Refill and Drillevator.
 

# Custom Waves
- During a Dreadnought fight (OG Dreadnought, Hiveguard, normal Twins), a Bulk Detonator known as a "DreadHelper" will spawn in to allow the team to kill the Dreadnought faster. Only one DreadHelper can exist at a given time. The DreadHelper moves x1.5 faster.
- As the same time as Dreadnought fight, a wave spawner's wave (the size is as big as normal wave) will spawn in immediately at the beginning of dreadnought fight, and will spawn again after 240s. 
- During a Caretaker fight, a weaker Bulk known as "CaretakerHelper" will spawn in to allow the team to speed up killing caretaker faster. Only 1 CaretakerHelper can exist at a given time, once no more CaretakerHelper is in the map but Caretaker fight is still going, they will respawn after 5s. CaretakerHelper has only 1000 Base HP (4000 HP normal bulk), with only x1.2 movement speed instead (normal bulk x1.5), and the carve radius is the same as minibulk. Its look is changed via CD2. Spawnspread is the same as DreadHelper Wavespawner. Freeze and Unfreeze temp is now only -240 & -100, and they warm slower than normal bulk.
- As the same time as Caretaker fight, a wave spawner's wave (the size is as big as normal wave) will spawn in every 180s.
- Every 60 seconds (80 seconds during Dread, Caretaker fight or Heartstone escort), either 14-20 Grunts with 1-4 White Spitters, a Bundle or/with 2-3 Mactera Spawns, or 2-3 Mini-Bulks spawn. Mini-Bulks from this WaveController are not allowed to spawn on Escort, and disabled during Defensive objective, Drillevator and Caretaker fight. Minibulk wave has a slightly higher chance to spawn compare to FC. Enemy amount is adjusted for the playercount (at 4p it will be always at max value.).
- Every 90 seconds, a Trawler spawns. This wave controller is disabled in 1 player count lobby. Up to 2-4-5 trawlers can be available in the map with 2/3/4p setting.
- Every 45 seconds (90 seconds during Refinery Stalling/Repair phase, 60 seconds during Dread, Caretaker fight or Heartstone escort), a mix of 2-4 weak Elite enemies will appear. The pool are: "0-2 Mactera Spawns, 0-3 Slashers, 0-2 Septic Spreaders, 0-1 Stingtail and 0-2 Ratters". In 1p setting, Elite Stingtail is removed from wavespawner pool. Stingtail once spawned will have a cooldown timer of 210s/140s in 2/3+ player setting before being able to spawn again in this wavespawner. During Drillevator, Elite Septic once spawned will have a cooldown timer of 210s/140s in 2/3+ player setting, in 1p setting it's never spawned during that aforementioned section.
- Every 110 seconds (145 seconds during Heartstone Escort), a Penta-jaw will appear (only appear in 4p setting or during EnemyCountMultiplier waves from what I've read from the file since this feature was brought back from FC).

# Miscellaneous:
- Bandaid bug fix: Darkness module somehow caused scout's flare gun to have significantly less duration time so i added FlareGunDuration field value in Darkness module file, so it matches 90s of duration (1 duration upgrade) most scout upgrade path will take.
