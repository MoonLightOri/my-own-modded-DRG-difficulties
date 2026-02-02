This difficulty used 6x2EX - a difficulty made by pH-JPEG, as a framework, but with adjustments. It's also a toned-down version of Celestial. Updated to v1.04.

Astral minimum requirement: Custom Difficulty 2 beta 13+, MEVv5_4 (Latest version is always better).

- Recommended Mods: 
  + VEA: https://mod.io/g/drg/m/vanilla-enemy-adjustments
  + No Special Swarms: https://mod.io/g/drg/m/no-special-swarms#3374117
  + Sabo with Stationaries & More Egg Swarms & Only Bug No Content & No Crawler Puddles (Use MINT to Install): https://drive.google.com/drive/folders/1E4UR8TwjofQM-b4SRm-pOf0bq4_qoYfL?usp=sharing

- Optional Mods:
  + More Egg Swarms (If you want a more challenging Egg Hunt): https://cdn.discordapp.com/attachments/1148725752020340827/1166128615440789546/more_egg_swarms_P.pak?ex=682ef0a7&is=682d9f27&hm=c21d0b1a6b76339885f8070ee82a954dd027619df1506a39824f347f1fdd8b42&

- Q: Why are Dread and Caretaker with normal wave mod not included in the recommended list above? 
  - A: My difficulty has a dedicated Wave Spawner to simulate normal waves during Dread and Caretaker with 100% accuracy. You don't need Dread and Caretaker with normal wave mod anymore since I've forced this into my difficulty.

* Legends: 
  + During Defense = Uplink/Refuel/Blackbox objectives.
  + 1/2/3/4 = Player Count setting (Left to Right, The last value in the list is used if there are more players than there are values in the list.).
  + 1p = 1 Player Setting.

# General (Mostly the same as 6x2EX)
- Enemy HP, Damage and Movement Speed scaling follows Hazard 6.
- Enemy Count Modifier values are 6x2 values increased by 10%.
- Initial resupply cost is 40 nitra, afterwards it raises to 50 nitra.
- Enemy projectile speed follows Hazard 6.
- Friendly fire is set to 90%.
- You revive with 30% HP and regen up to 30% of your HP compared to the typical 10% seen in Hazard 5 and other modded Hazards. You begin to regenerate your HP after 6 seconds if you don't take any damage. It takes 10 seconds to regenerate from 1 HP to 30% HP once the regeneration begins.
- Dorretta resists 75% of damage (Higher in Solo in certain scenarios); it is the same as the value used in 6x2.
- Whenever an Egg is pulled, if it does not trigger a swarm, the wave it summons spawns x2 the bugs.
- Wave timers are technically based off of Hazard 6.
- High enemy diversity in waves.
- Most caves will have at least one of every Stationary type if possible.
- Many new enemies have been added in the form of enemies that normally don't spawn in waves and entirely new enemies from CD2, MEV and DEA.
- Some existing enemies have been modified (E.G: Some enemies having lower freezing temperatures like Breeders, Bombers and Patrol Bot. Elite enemies have lower burn and freeze temperature,... - Having some favor for Cryo comp.).
- Custom waves of certain enemies spawn at set intervals or conditions.
- Difficulty adjusted across mission types (E.G: Escort heartstone phase gets slightly easier).
- During Defense, reduce Progress Bar Penalty by 20%. At 1p, also increase Bubble radius by 25%.
- Rival Turrets spawn count in Encounters sabotage mission type is reduced by 35%.
- Lower player scaling (Especially Solo) will have signficant change on Enemies, Objectives and Mission types to make playing easier. (E.G: Doretta during Refill and Heartstone phase gains slight increased resistance. No Bulk spawns during Defense...)
- Disabled player headbounces.
- Banned Blood Sugar, Low Gravity, Duck and Cover, Ebonite Outbreak and Lithophage Outbreak warnings.

# Enemies
- Swarmer
  + They are now stunnable.
  + Base HP 12 -> 4.
- Sentinel
  + They are the bugs the Dreadnought Hiveguard summon. Electric Weakness +30%.
- Leech
  + They grab and damage +30% faster.
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
  + Their Direct hit damage -15%, and have slight material change.
- Breeder
  + They have Base HP -50%. 
  + A Breeder can sometimes respawn in a wave.
- Patrol Bot
  + They spawn globally independent of Rival Presence or Industrial Sabotage.
  + No longer do Bump Attack (You take damage and get knocked back).
- Nexus
  + They have Fire Damage Weakness +295%. 
  + They now instead spawn white normal Grunts that only have 70 HP.
- Grabber
  + They spawn spread out from waves. There is 20% chance to promote into Deliverer instead.
- Deliverer (CD2)
  + They move -50% slower and have Fear immunity. Their materials are changed slightly.
  + They won't flee away or drop you down after taking damage.
- Bulk Detonator
  + They move +30% faster. 
  + They also tend to spawn far from the team. On an Escort, they spawn at a normal distance from the team.
- Ice Detonator (MEV)
  + They move +30% faster, and is rarer than Bulk Detonator.
  + Stomp and Explosion damage type changed to Cold damage, which will instantly freeze you.
  + Leave no Meetball on Explosion but have a larger damage range and blast player away.
- Flying Rock from Heartstone phase
  + Base HP 250 -> 90/120/148 (same Base HP as Grunt/Acid Spitter/Slasher).
- Trawler (Spawn on Sandblasted)
  + They have Time Dilation -25%. 
  + Maximum spawn on field reduced to 0/2/4/5.
  + Banned in 1p.
- Oppressor
  + They move +25% faster. 
  + Maximum spawn on field reduced to 3, and 1 during Defense and Hacking. At 1/2p, this number in both scenarios is reduced by 2/1 respectively.
- Stalker
  + No longer spawns in Solo.
  + Damage Dealt -50%.
- Elite Grunt Slasher (CD2)
  + They spawn globally independent of Elite Threat, and only spawn via custom Wave Spawner. 
  + Has 265/274/309/336 HP (based on Crawler Normal Scaling at 4p), and material change.
- Glyphid Architect (CD2)
  + It is a rare menace variant that has Base HP x0.7855 and Time Dilation -25%. Its material is changed also.
  + Normal projectile is now the default (No Upgrade) Engineer's Platform. Its purpose is to disrupt surrounding terrain around players. 
- Line-Cutting Turret (CD2)
  + They are Repulsion Turrets that have their material changed and now shoot slow Breach Cutter projectile.
  + Stationary unit.
  + Burning won't self-destruct them. Burning and Freezing temperature is now lower than normal.
  + It cannot be spawned on Escort mission type.
- Korlok Sprouts (MEV)
  + Stationary unit.
  + They can spawn only on the ground and start off sleeping until they take damage.
  + Base HP -1/6. Its material is slightly changed to shine in the dark.
- Spitscreener (CD2, MEV)
  + They are more expensive Spitballers that have Time Dilation -33.33%. Their material is changed also.
  + Stationary unit.
  + Projectile they shoot is triple Nemesis's barriers.
- Big Shredder (CD2)
  + They spawn in a pair. Base HP x12.82, Damage Dealt +100% and is immune to Fear.
  + They don't have any weaknesses of small shredders.
- Vomit Spitter (CD2)
  + They are ground Web Spitter that spit Barrager's vomit projectile in an arc. Their material is changed also.
  + Use Acid Spitter's AI, mean that they will aggressively shoot at you once they stop moving.
  + They shoot in higher arc in Astral, which lead to lower accuracy.
- Barrier Shooter (CD2)
  + They are Acid Spitter that spit Nemesis's barrier. Their material is changed also.
  + Use Web Spitter's AI, mean that they will reposition after shootting once.
  + They move +50% faster.
- Crawler
  + They can spawn in waves globally independent of the Core Stone event.
- Barrage Infector
  + They are rarer than usual and are even rarer on Escort.
- Scalebramble (CD2)
  + They are rarer than usual. Only one can spawn on Escort. They are time dilated to half speed.
 

# Custom Waves (Wave Spawners)
- During a Dreadnought fight (OG Dreadnought, Hiveguard, normal Twins), a Bulk Detonator known as a "DreadHelper" with Base HP x0.85 will spawn in to allow the team to kill the Dreadnought faster. Only one DreadHelper can exist at a given time.
- During Dreadnought or Caretaker fight, Normal Wave will spawn in periodically. For Dreadnought fight, the Interval is increased by 50, but the beginning of the fight will guarantee a Normal Wave spawn.
- Every 125 seconds (Longer during certain pressure scenarios), 8-11 non-promoted Grunts spawn.
- Every 100 seconds (Longer during certain pressure scenarios), 1-2 weak Elite Slashers spawns in. This wave spawner no longer spawns in 1p setting.
