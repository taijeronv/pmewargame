---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NGW Concept Document"
subtitle: ""
summary: ""
authors: [TJ]
tags: ["design", "concept"]
categories: ["Wargame"]
date: 2020-01-09T06:54:37+02:00
lastmod: 2020-01-09T06:54:37+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Easy to play computer wargame that provides an operational environment to
practice tactical decision-making and problem-solving. 

## Genre(s)
Wargame

## Target audience
- Students enrolled in a professional military education program like West Point or ROTC. 
- Military instructors who want to provide a complete experiential learning experience. 
- Military professionals who want to practice solving tactical problems.

## Unique Selling Points
- Designed specifically as a teaching tool.
  - Records the game allowing for a more detailed review.
  - Lightweight modeling of most of the warfighting functions.
  - Easy to use interface.
  - Automated behaviors reducing the need to micromanage.
- Playable inside a web browser.
- Delivered over the internet or Local Area Network.
- Operating system does not matter.

Recording the game allows the student review their decisions.  This is very important because it allows them to do a more detailed analysis as to why they made certain decisions.  This is where the real learning takes place.  

## Player Experience
The player should feel as if they are commanding their units.

The player should also "command" at the appropriate level.  For example if it's a battalion operation they should be making battalion-level decisions.  Keep in mind that without "automated forces" this can be difficult to achieve.  My thought on this is to model two levels down, which means in a battalion level simulation the player will be moving platoons and in some cases sections. 

## Visual and Audio Style
The map is simply a background image that is used as a reference by the player.  The "terrain file" is where the data goes that affects combat, movement, and spotting.

The ideal situation is to use a scanned image of a military topographic map, but you can always create your own custom map.  For example this is a map I created for Follow Me.

One of the options I plan to explore is the use of cloud based maps like Google Maps.  

## Game World 
The game world is represented by enemy, terrain, and weather. 

## Technology, and Scope (brief) PC or mobile?
- Meant to be played inside a web browser.
- Delivered over the internet or LAN, operating system does not matter.
- Javascript using the [Phaser game library](https://phaser.io/).
- Frontend web technologies to create the website.

## Objectives and Progression
The player begins by choosing a scenario. The scenario file serves to purposes.  The first is to provide the user with information regarding the situation, mission, and objectives.  The second purpose is to load the appropriate map image, unit, and terrain data.

The general course of play is pretty straightforward:
1.  Plan the next turns moves and combat.
2.  Enter orders for each unit that you want to perform an action.
3.  Execute a turn.  At this point the "computer umpire" takes over and performs game functions like moving units, all forms of combat, and other administrative game functions.
4.  Repeat steps 1-3.

The game ends when one side accomplishes their mission or their force has been defeated or neutralized and can no longer operate. 

The entire game is "recorded" so the player can study the operation in greater detail.

## Game Systems 
The simulation model is an abstraction of all the warfighting functions and can be calibrated to produce believable results.

The graphics engine is fairly basic and the animations can be easily handled by the Phaser framework. NGW is not a 3d game.

A detailed and configurable AI is a critical part of the system. This enables content creators to develop realistic enemy behavior and provide a challenging operational environment for the player.

Events are also important.  It allows the content creator to trigger specific decision-making events that require some decision to be made.  By using events we can create multiple situations in one scenario.  

## Interactivity
The user interface is simple and designed to be intuitive. Orders are given by right-clicking on the unit and selecting the appropriate order. Automated unit behavior can be configured so the player does not have to micro-manage their units. For example automatically engaging an enemy units under certain conditions or prioritizing what target to shoot first based on user-defined criteria.