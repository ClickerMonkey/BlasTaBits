# Gameplay

This document contains the direction for the gameplay - there will be tags to note `future` features.

- [Overview](#overview)
- [Weapons](#weapons)
- [Abilities](#abilities)
- [Perks](#perks)

## Overview

The game type defines "points". These points can be # of kills, time accumulated, # of flags captured, etc. You play until the match is resolved. The game type can define initial weapons, weapon restrictions, as well as weapon spawns & ammo. Every game type can have unique respawn options and game modes.

Team Arrangements:
- Free-for-all
- Team based

Match Resolutions:
- Time based (ranked by points)
- Point limit reached

Weapon Selections:
- User's default.
- The user must select N number of weapons or has X number of points.
- User can only build their profiles based on certain weapons/ability/perks.
- The user starts with a fixed weapon.
- The user starts with a fixed weapon and as they get to certain points they are given a new weapon.
- Weapons/ammo could spawn and be picked up to replace the current weapon (there could be a max which restricts too many large weapons).

Respawn Options:
- Random location
- Random location from points/areas
- Waits until a point changes (kills, captures, etc)
- Waits until X seconds elapses
- Allow user to select from predefined points/areas
- Switch sides?

Game Modes:
- Normal
- Capture the flag
- Defend a base
  - The base could be a fixed location OR could move after each defense. 
  - There could be a "capture" limit on the base (either you get points, it relocates, or you get "possession" which may give you additional points)
- 

With these options you should be able to derive the following game modes:
- Deathmatch
- Team Deathmatch
- Retrieval (Two teams, one defends bases the other needs to capture. Once captured, the bases can relocate. After X captures or time amount reached, switch sides)
- Capture the Flag (Take players flag and bring it back to your base. If you're killed, the flag must be picked up by the opposing team to be returned (either manually or automatically) or it's teleported back).
- 

## Weapons

### Guns
- Pistol
  - A short range weapon with high rate of fire.
- Rifle
  - A long range weapon with medium rate of fire.
- Rocket Launcher
  - Launches a rocket propelled timed & touch sensitive.
- Replicator `future`
  - Copies & Shoots Blocks
  
### Magic
- Spawner (wall, pillar, bunker, steps) `future`
  - A medium rate of fire with medium default ammo.
- Tunneler `future`
  - A slow rate of fire with low default ammo.
  
### Grenades
- Pineapple Grenade
  - A timed explosive.
- Sticky Grenade
  - A timed explosive which sticks to the first surface it comes in contact with.
- Bouncy Grenade
  - A timed explosive which really bounces around.
- Creation Grenade `future`
  - A timed explosive which spawns a random structure.
  
### Mines
- Proximity Mine
  - An explosive triggered by enemy coming within certan distance.
- Sound Mine
  - An explosive triggered by line-of-sight with an enemy.
- Detonation Mine
  - An explosive triggered by the user.
- Pressure Mine
  - An explosive triggered by touch.

### Mines & Stick Grenade

If the surface it's stuck to is removed, the projectile will fall to the ground.

## Abilities

- Wall Jumping
- Wall Running
- Boostpack `future`
  - A limit fuel populsion system.
- Jetpack `future`
  - A charge based propulsion system.
- Aqualung `future`
  - Quickly move through water.
- Teleportation `future`
  - Choose a block to teleport to the top of. Restricted by distance and either use count or "recharge" time.

## Perks

- Sentry Gun `future`
  - 
- Spawn Defensive Tower `future`
