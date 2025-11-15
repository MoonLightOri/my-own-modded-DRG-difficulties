This difficulty used Interstellar and Send It! Type R as a framework, but with adjustments. Updated to Alpha 06.

Contributor: seu (for certain enemies)

Interstellar requirement: Require CD2 beta 15b+, MEV v5_4, DEA b01.1.0 and EEE v1.5.4 (Latest version is always better).

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
- The game will start ticking down the Threat Meter (Displayed as boss bar) after 15s of starting. There are 5 levels of Threat which increase the difficulty, interval and enemy composition of Normal Wave. Every phase transition will force spawn a normal sized wave (which can stack with the current Normal Wave spawner). Here's the detailed section for each threat:
  + Threat Lv1: LOW. Take 180s to reach Lv2. Main Normal Wave timing is 37.5s.
  + Threat Lv2: MODERATE. Take 270s to reach Lv3. Main Normal Wave timing is 37.5s. Some Enemies are now able to spawn (The Jupiter, Fire Bomber, Sentinel, Naedocyte Breeder in Swarm, Patrol Bot, Architect, Barrier Shooter, Vomit Spitter). Bulk Detonator now moves 35% faster.
  + Threat Lv3: SUBSTANTIAL. Take 360s to reach Lv4. Main Normal Wave timing is 30s. Some Enemies are now able to spawn (The Sun & Moon, Elite Grunt Guard, Turbo Menace, Mini-Bulk, Ninja, Naedocyte Seeder). Bulk Detonator now moves 35% -> 50% faster. Nexuses now spawn White Weak Slasher (previously White Weak Grunt). Swarmer Tunnel and Egg Spider now spawn tanky Glyphid Rat enemies (Previously White Weak Grunt). Naedocyte Breeder now spawn White Exploder. Normal Exploder and Grabber now moves 50% faster. Oppressor moves 20% -> 50% faster. Every 100s, Lacerator or Arbalest will spawn via Mini-Boss WaveSpawner. Enemy Movement Speed increases from Hazard 6 value to Hazard 7.
  + Threat Lv4: SEVERE. Take 450s to reach Lv5/Max. Main Normal Wave timing is 30s. Fanatic and Grenade Spitter are able to spawn. Septic can now be promoted into Ice Septic variant. Youngnought and Ice Youngnought are now able to spawn via Mini-Boss WaveSpawner. Enemy Attack Cooldown (mostly for grunt) increases from Hazard 6 to Hazard 7.
  + Threat Lv5/Max: CRITICAL. No longer drains once the Threat level is 5. Main Normal Wave timing is 25s. Mactera Warden, Rat Bomber and Barrinator are now able to spawn. Oppressor now moves 50% -> 100% faster. Grabber can now be promoted into Deliverer. Solaris and Joker are now able to spawn via Mini-Boss Wave Spawner. Every 60s, PhaseBomb can spawn to bomb the players. Enemy Damage Modifier increases from Hazard 6 to Hazard 7.
- For every 50 Gold into Team Repository (Counted by dividing 40 in repository) will increase the gauge by 90s immediately. This is crucial to delay the timer.
- When 2+ players repairing Mini-mules/Uplink/Refuel, increases the repair speed. Also reduce the time to scan Mini-mule legs to 1 second.
# New Enemies compare to Interstellar:
- Grenade Spitter (Lv4): 
  + It's a rare Acid Spitter variant
  + Instead of spitting Acid projectile, it spits Gunner's Grenade, deal moderate damage in an AOE range.
- Phase Bomb (Lv5): 
  + Nemesis immediately dies when spawned, thus spam bomb on player position.
- The Jupiter (Lv2):
  + Has 400 Base HP and Bigger Hitbox than The Sun and The Moon.
  + Can bleed after a certain times.
  + When it dies, spawn one of the three attack and cycle in order for the next Jupiter spawn: Meteor Rain -> Helium Rain -> Gravitational Field -> (repeat).
    + Meteor Rain: Spawn a burst of meteor rains (A lot of Flying Rock) that fly around until they hit the terrain. Deal high amount of damage when player is hit with Flying Rock and can carve terrain.
    + Helium Rain: Spawn a burst of particle (dying Foobers) that drops bomblet on player, deal damage on contact.
    + Gravitational Field: Spawn an invisible Field (Invisible Stingtails) that can instantly grab player in range and repeatedly make the player stuck in place, however they deal no damage.
- Gas Spreader (Lv4): 
  + Another Septic Variant
  + Shoot a projectile that generate Praetorian Death Cloud (Non-combustable), dealing damage via the projectile impact and death cloud.  
- Invincible Exploder (Lv4): Unkillable by normal mean, but will die after self-exploding like normal.
- Teleport Praetorian (Lv3): 
  + This enemy teleports and rotates hit target in 5m range. 
  + On death leaves field which applies STE_DimensionalInstability and will cause player to teleport randomly every 5 seconds within Death Radius (Ste has 15 seconds duration). 
  + Have higher movement speed but less health. 
  + This enemy replaces Fire Praetorian previously.
- Grunt Grooter (Lv2): 
  + A hybrid of Grunt and Acid Spitter.
  + It can shoot triple Barrager's projectiles (Deal only 50% of damage) and will move to the player to attack player directly, dealing slasher-like damage and poison DoT. 
  + This enemy replaces Vomit Spitter previously.
- George (Lv5 Mini-boss WaveSpawner): 
  + This is a trijaw which has smaller hitbox and take longer time to shoot. 
  + It shoots 72 of trijaw projectiles in radial pattern. 
  + Unfearable.
- Fire Youngnought (Lv4 Mini-boss WaveSpawner): 
  + This is fire variant of Youngnought. 
  + It shoots Scorching Tide projectile, Lacerator's flame attack and Normal Stomp.
- Praetor Youngnought (Lv4 Mini-boss WaveSpawner): 
  + This is a praetorian variant of Youngnought.
  + It can do sonic stomp which deals low damage but knockback player a significant amount. Also can do Normal Dreadnought stomp.
  + Projectile ball attack can spawn Combustable Praetorian Death Cloud.
- Banshee (Lv3 Mini-boss WaveSpawner): 
  + This is another variant of Arbalest. 
  + It will only do grieve attack which launch Snowball projectile to freeze player (Player will need to take atleast 2 snowballs directly to be completely frozen)
- Bayonet (Lv3 Mini-boss WaveSpawner): 
  + This is another variant of Lacerator. 
  + Replacing the stomp attack, it can launch triple arc-fireballs attack to player. 
  + Occasionally can shoot a singular fireball too.   
- Shade: 
  + Upon dying, spawn a series of Event which cause darkness, losing Shield and slowed down.
- Venus:
  + Has 300 Base HP and Bigger Hitbox than The Sun and The Moon.
  + Can bleed after a certain times.
  + Upon alive, spawn flaming projectile nearby player, deal fire damage constantly.
- Blackhole: It's a big Shredder that makes you take fall damage when jumping from any height (Will notice when it's about to spawn in chat).
- Uranus: It's a Radial Jaw that Sprays Snow everywhere.
  # Custom Waves
- During a Dreadnought fight (OG Dreadnought, Hiveguard, normal Twins), a Bulk Detonator known as a "DreadHelper" with Base HP x0.85 will spawn in to allow the team to kill the Dreadnought faster (Highlighted by Item Outline, disappear after being pinged by player and expire). Only one DreadHelper can exist at a given time.
- During a Caretaker fight, a Weak Bulk Detonator known as a "CaretakerHelper" with slower movement speed and Base HP x0.25 will spawn in to allow the team to speed up Caretaker fight (Highlighted by Item Outline, disappear after being pinged by player and expire). It has halved carve radius compare to Normal Bulk. Only one CaretakerHelper can exist at a given time. Its material is slightly changed to distinct from Bulks that spawn from Waves.
