As Astral is still a WIP difficulty, this feature list may be subject to change. This list is updated to a04 version.
This difficulty used 6x2EX - a difficulty made by pH-JPEG, as a framework, but with adjustments. It's also a toned-down version of Celestial.

# General (Mostly the same as 6x2EX)
- Enemy HP, Damage and Movement Speed scaling follows Hazard 6.
- Enemy Count Modifier values are 6x2 values increased by 10%.
- Initial resupply cost is 40 nitra, afterwards it raises to 50 nitra.
- Enemy projectile speed follows Hazard 6.
- Friendly fire is set to 90%.
- You revive with 40% HP and regen up to 40% of your HP compared to the typical 10% seen in Hazard 5 and other modded Hazards. You begin to regenerate your HP after 6 seconds if you don't take any damage. It takes 10 seconds to regenerate from 1 HP to 40% HP once the regeneration begins.
- Dorretta resists 75% of damage; it is the same as the value used in 6x2.
- Whenever an Egg is pulled, if it does not trigger a swarm, the wave it summons spawns x2 the bugs.
- Wave timers are technically based off of Hazard 6.
- High enemy diversity in waves.
- Most caves will have at least one of every Stationary type if possible.
- Some of the enemies can also be promoted into new type of enemies, with own's custom veterans chance.
- Many new enemies have been added in the form of enemies that normally don't spawn in waves and entirely new enemies from CD2, MEV and DEA.
- Some existing enemies have been modified.
- Custom waves of certain enemies spawn at set intervals or conditions.
- Adjusted mission types enemycount mostly to be more balanced, harder in Refinery refining phase, Hacking phase in Sabotage and Drillevator. Slightly easier on Escort Final phase 1 and 2, before Hacking 1 and Caretaker phase in Sabotage, and normal and pressure wave of Deep Scan.
- During the time of Uplink/Refuel/Blackbox objectives, Mission Control will no longer shout at you with "Get back to the triangulation zone! We're losing you" type of quotes if you no one is at triangulation zone.
- Disabled player headbounces.
- Breeder type enemies have lowered Freeze temp.
- Rival turrets and Patrol Bot enemies have lower freeze temp.
- Lower player scaling will have some change to the existing enemies to make playing easier, especially in 1p setting. Such as: Barrager type enemies MaxSpawnCount reduced to 0, and they gain even less SpawnAmountModifier than before. Bulk type enemies are banned during 1p defensive objective. Shockers have added NoSpawnWithin in 1/2p setting, and have spawncount significantly reduced in 1p setting.
 
# Enemies
- Canary
  - This is a giant Swarmer that spawns at the start of every mission. Its sole purpose is to test client desync. If clients cannot see a giant Swarmer or the boss health bar it creates, they are desynced and should try rejoining.
- Sentinel
  - These are the bugs the Dreadnought Hiveguard summon. They also have Electric weakness by 30%.
- Leech
  - These move x1.25 faster. However, if a Leech from high up grabs you and it's killed, you will not die of fall damage.
- Fire Bomber
  - This is an unused enemy in the game files. It behaves like a normal Goo Bomber, except it drops bomblets that deal extreme damage to players.
- Breeder
  - These take x2 damage. A Breeder can sometimes respawn in a wave.
- Patrol Bot
  - These spawn globally independent of Rival Presence or Industrial Sabotage. Damage taken is increased to x3 when being Frozen. At 1p setting, MaxSpawnCount is reduced to 0.
- Nexus
  - These take x3.95 fire damage. They also spawn white normal Grunt from MEV that only have ~70 HP.
- Grabber
  - These spawn spread out from waves. They have 30% chance to promote into Deliverer.
- Deliverer (CD2)
  - This is a promoted type of grabber that has 20% more HP than normal Grabber and 50% slower time dilated. Instead they have fear immunity, and won't flee away or drop you down once you're grabbed. Its look is the same as normal grabber, only name change.
- Bulk Detonator
  - These move x1.3 faster. They also tend to spawn far from the team. On an Escort, they spawn at a normal distance from the team.
- Ice Detonator (MEV)
  - These are the rare MEV Bulk type that moves x1.3 faster, spawn far from the team and its attack and explosion will cause freeze damage instead. Explosion leaves no meatball but it will blast players away if they are caught within the explosion zone. Explosion size is reduced by 33.33%. It's weakpoint is changed and now glow in the dark via CD2.
  It's explosion damage radius and max damage radius is reduced by 20%. It's banned in Defensive Objective and in Drillevator. 
- Glacial Praetorian, Glacial Bomber
  - These spawn globally in all biomes.
- Oppressor
  - These move at x1.3 speed, x1 speed if 1p setting. If 2 or more Oppressors are present on the map, no more Oppressors will spawn in, this number is decreased to 1 on 1/2p setting. During the Uplink/Fuel Cells/Black Box, 0 Oppressor will spawn in 1p setting. For other players setting, if 1 or more Oppressors are present on the map during the Uplink/Fuel Cells/Black Box, no more Oppressors will spawn in.
- Stalker (Beta Stalkers)
  - These are replaced with their Beta version. Set your Effects in the in-game options to High to see them while they are cloaked.
- Elite Grunt Slasher (CD2)
  - Elite Slasher spawn globally independent of Elite Threat. Mostly spawn from wave spawner, with its look modified and are slightly bigger sized. It also has lower burning and freezing temperature compare to vanilla elite Slasher, but the number is still higher or equal to normal enemy type. It also takes x3.2 more damage than usual.
- Glyphid Architect (CD2)
  - This is a yellow aura colored menace that has the base HP of a vanilla Korlok Sprout and shoots Engineer's platform rapidly with 25% slower time dilation. Its look is heavily modified by CD2. There can only be 1 Architect in the map and is now made even more expensive and rarer to spawn compare to Celestial difficulty.
- Line-Cutting Turret (CD2)
  - These are the modified bigger-sized Repulsion turret via CD2, made into every mission type and spawn as Stationary unit. It has the same HP as repulsion turret (600 HP) which is 50% faster time dilated and shoots Line-Cutting projectiles from OMEN Tower in many direction upon alerted. It's also immune to dying after being on fire, has freezing temperature of -200 celcius and take x3 more damage once frozen. It's banned in Escort due to its fast frequency and many lines on lazer beam which can deal ridiculous damage to Dotty.
- Sniper Turret
  - They cost more DifficultyRating to deploy now so the number will be lesser in Hacking room in Sabotage mission.
- Korlok Sprouts (MEV)
  - Added from MEV, Sprouts spawn as Stationaries similar to Nexuses, Leeches, Breeders, and Spitballers. These can spawn only on the ground and start off sleeping until they take damage. These take x1.2 damage.
- Spitscreener (CD2)
  - These are the modified look of normal Spitballer, spawn as Stationary unit which shoot one Nemesis's barrier in each shot toward your team. Made to be rarer than normal Spitballer and possibly Nukeballer. They spawn even less in pack in 1p setting. Its projectile count is nerfed in this difficulty compare to Celestial difficulty.
- Big Shredder (CD2)
  - Possible with CD2, this is just a big Shredder that spawns alone or in a pair. It deals normal Shredder damage, but it has about x13 the HP of a normal Shredder. They are made to be rarer in this difficulty compare to Celestial difficulty.
- Vomit Spitter (CD2)
  - These are another type of ground acid spitter which shoot Barrage Infector's vomit projectile. Its look is changed via CD2. This version is a toned down version from Celestial and Interstellar which has higher arc, lower projectile speed and it can sometimes stuck the projectile on the ceiling. 
- Barrier Spitter (CD2)
  - These are another type of acid spitter which has slightly bigger look, and spit at x0.75 speed. The projectile they spit is Nemesis's Barrier. Its look is changed via CD2.
- Crawler
  - These can spawn in waves globally independent of the Core Stone event.
- Barrage Infector
  - These are rarer than usual and are even rarer on Escort.
- Scalebramble (CD2)
  - These are rarer than usual. Only one can spawn on Escort. They are time dilated to half speed.
 

# Custom Waves
- During a Dreadnought fight (OG Dreadnought, Hiveguard, normal Twins), a Bulk Detonator known as a "DreadHelper" will spawn in to allow the team to kill the Dreadnought faster. Only one DreadHelper can exist at a given time. The DreadHelper moves x1.3 faster.
- At the start of a mission, a Canary or two spawns in. It is a big, slow swarmer with a boss HP bar. It is meant to detect desync between clients on CD2.
- Every 100 seconds, either 8-11 Grunts (Not promoted into veterans) spawn. Enemy amount is adjusted for the playercount (at 4p it will be always at max value.).
- Every 85 seconds (170 seconds during Refinery Stalling/Repair phase), a 1-2 weak Elite Slashers spawns in. This wavespawner is banned in 1p setting.
