# 2025 Big Data Bowl
## Goal

NFL offenses have 40 seconds in which to run a play. That time begins with substitutions, as players run on and off the field until both teams' personnel are configured. It continues into the play call, where both the offensive and defensive units learn their formation and assignments. It ends with myriad strategic decisions by the 22 players on the field, including motion, shifts, and alignment changes, designed to both confuse the opponent and capitalize on any advantages.

In all that action prior to the snap, both teams likely divulge patterns in what players will do after the snap. The goal of this year's competition aims to tell us just what those patterns are.

Your challenge is generating actionable, practical, and novel insights from player tracking data corresponding to pre-snap team and player tendencies. Examples include, but are not limited to:

Play prediction (run v pass)
Scheme prediction (blitzes, run fits, route combinations, etc)
Player prediction (pass patterns, blocking assignments, etc)
Note that the above list is not exhaustive, and we encourage participants to be creative with their submissions.

## First Thoughts

The data here is from 2022. Let's look at macro NFL trends going into that season

- Common coverage types
    - Offensive Success vs the coverage

Motion Types
- Shift -> multiple players go into motion but must become set
- Motion -> is going to be followed if defense is in man coverage
    - can force a defense to show you WHICH zone


2023 Miami Dolphins pre-snap motion success

## Idea 1: Unveiling Defensive Types using Types of Motion

Using different types of pre snap motion
- can you reliably infer coverage scheme
- should I run / pass, which way
    - assign which route(s) / route combinations have the highest probability of success
    - which run lane should I attack

Types of pre-snap motion: https://www.viqtorysports.com/pre-snap-movement-in-the-offense/

RouteNet: https://operations.nfl.com/media/3671/big-data-bowl-sterken.pdf

## Motion vs No Motion

Success of each play type with
- no motion
- motion towards the play
- motion away from the play

## Background

Teams run zone with deep shells to negate big plays
- how did Mike McDaniel exploit this?

Teams run man if they want to blitz or think they have advantages

## External Resources

- https://github.com/kinne174
    - Previous BDB entries that could be helpful

## Features

### Offense

- Motion Type

- Motion Direction


### Defense

- Adjustments 