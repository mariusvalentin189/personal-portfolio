---
title: "Snack Stack Fruits"
date: 2026-06-08
summary: "3-Match Game"
tags: 
  - Unity
  - Game-Dev
  - 2D
  - 3-Match
tech_stack:
  - Unity Engine
  - C#
links:
  - type: github
    url: https://github.com/mariusvalentin189/Snack-Stack-Fruits
    label: Code
  - type: live
    url: https://mariusdev.itch.io
    label: Demo
featured: true
status: "In Progress"
role: "Game Developer"
duration: "2 months"
team_size: 1
highlights:
  - "3-Match game"
---

A 3-Match game that uses the basic 3-Match games rules.

## Overview

Developed a 3-Match game that uses the basic 3-Match games rules. The game has 10 level with increasing difficulty. The game does not have the power ups system used in many games of this type. The main purpose of this project was to implement the algorithm for this type of game.

## Challenges & Solutions

### Challenge 1: Game mechanics
**Problem**: Game mechanics need to be implemented in such a was that it does not match unwanted pieces at any point.

**Solution**: The core gameplay mechanics were implemented: matching tiles on each of possible combinations, spawning new pieces on top that fall and check again for matches.

### Challenge 2: Levels
**Problem**: Level building: manual vs random.

**Solution**: Built the level with random pieces. This added a challenge: spawn the pieces so taht no match happens on spawn. For this an algorithm was implemeted to check for matches on tile spawn.

### Challenge 3: Difficulty
**Problem**: Make level harder but possible.

**Solution**: Each level has a higher board and higher number of types of tiles to spawn. Levels have a star system wich rewards a number of stars from 0 to 3 based on the score at the end of the level.


---

**Project Status**: 🛠️ In progress 
**GitHub**: [View Source Code](https://github.com/mariusvalentin189/Snack-Stack-Fruits)
