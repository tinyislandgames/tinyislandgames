---
title: "Build 212 - Difficulty Adjustment"
tags: ['Plains of Havoc']
date: 2024-11-10T18:14:27+11:00
draft: false
---

## Bugfixes
- Fixed text on Greedy Hands
- Fixed Arc Splitter not properly halving arcs when splitting
- Fixed "Phantom Flames" burning when the enemy had died
- Fixed a bug where Overgrown could be chosen without its prerequisite
- Fixed an infinite-level bug
- Fixed settings menu navigation
- Fixed Embrittle calculation causing enemies to be one-shot
- Fixed wrong Draugr's spawning after defeating the boss in Svartalfheim

## Performance Improvements
- Fixed lag spikes due to a couple of audio files not pre-loading at game start
- Various other small performance improvements

## Additions
- Added a new achievement
- Added Leaderboard buttons to toggle between Top 100 and your own rank
- Added a custom cursor

## Changes
- Capped Corpse Explosion damage at max health of the exploding enemy
- Flying enemies can now spawn in the void
- Changed overall enemy difficult scaling
- Embrittle damage per stack from 0.25 to 0.005 for both ranks
- Fixed Combat Roll not actually granting additional rerolls