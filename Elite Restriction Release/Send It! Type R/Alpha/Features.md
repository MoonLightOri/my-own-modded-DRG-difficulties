* Changelogs [Base Difficulty Transfered from 6x2EX ERR]:
- Some of the Send It! Type R features (Hazard 7 Movement Speed, small encounter difficulty and small wave difficulty).
- Nitra Cost kept the same as 6x2EX ERR (40 -> 50).
- Small wave now uses WaveSpawner to handle, so now it will spawn in every mission types regardless if Normal Wave is disabled in Scenario or not. With this in mind, ECM will be reduced when Additional Swarm is hit in some mission types to prevent the waves being too big. PE has Distance spawn being 35m instead of usual 17.5m.
- When a downed player is detected, the wavespawner will be paused for 12.5s (Can be refreshed), then continue to tick the wave timer after it expires.
- Removed previous 6x2EX WaveSpawners because we have Send It! Spawner function already.
- Elites now have increased cooldown timer:
  + Most Elites have +50% CD normally. 
  + Praetorian and Oppressor variants have +80% CD increment instead (Elite Oppressor hidden CD is also +50%). 
  + CD increment doesn't affect Elite Breeder.
- Vartok now only spawns once in every mission type.
- Both Barrage Infector variants have DifficultyRating 200 -> 250.
- Normal Bulk has 33.3% -> 50% chance to be promoted into Elite Bulk.
- Sentinel has 20% -> 25% chance to be promoted into Elite Sentinel.
- During Drillevator Section in Deep Scan, Enemy Movement Speed will be increased by ~30%.