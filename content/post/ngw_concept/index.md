---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The NestGen Wargame"
subtitle: "Core Concepts"
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
Easy to play computer wargame that provides a dynamic operational environment to
practice tactical decision-making and problem-solving. 

## Genre(s)
Wargame

## Target audience
- Students enrolled in a professional military education program like West Point or ROTC. 
- Military instructors who want to provide a complete experiential learning experience. 
- Military professionals who want to develop their tactical thinking.

## Unique Selling Points
- Playable inside a web browser.
- Delivered over the internet or Local Area Network.
- Operating system does not matter.
- Designed specifically as a teaching tool.

## Player Experience and Game POV
The player should feel as if they are commanding their units.

## Visual and Audio Style
Talon is played on military topographic maps or something similar to google maps. Unit icons represent platoons, squads, or sections using NATO symbols or vehicle/equipment silhouettes. Battlefield sounds and animations provide player feedback.

## Game World 
The game world is represented by enemy units, terrain, and weather all of which have an impact on the operation. 

## Monetization
- Subscription via website.
- Custom game setup on a LAN.
  
The game or subscription can be customized based customer needs.  For example if a more detailed combat model is required, or they want access to
more advanced content. The LAN setup is meant for organizations that do not want to deal with the internet.

## Technology, and Scope (brief) PC or mobile?
- Meant to be played inside a web browser.
- Delivered over the internet or LAN, operating system does not matter
- Javascript using the [Phaser game library](https://phaser.io/).
- Frontend web technologies.

## Objectives and Progression
The player begins by choosing a scenario. The scenario contains information regarding the operation such as the mission, friendly troops available, map,
objectives, and intel reports. The scenario file contains data used by the game engine for various functions and calculations.

The player plays the game by giving orders to their units like move, attack, defend. Orders are based on doctrinal tasks.

The player continues playing until they accomplish the mission or their force has been defeated or neutralized and can no longer operate. The entire game is "recorded" so the player can study the operation in greater detail.

## Game Systems 
The simulation model is an abstraction of all the warfighting functions and can be calibrated to produce believable results.

The graphics engine is fairly basic and the animations can be easily handled by the Phaser framework. NGW is not a 3d game.

A detailed and configurable AI is a critical part of the system. This enables content creators to develop realistic enemy behavior and provide a challenging operational environment for the player.

Events are also important.  It allows the content creator to trigger specific decision-making events that require a response.  By using events we can create multiple situations in one scenario.  

## Interactivity
The user interface is simple and designed to be intuitive. Orders are given by right-clicking on the unit and selecting the appropriate order. Automated unit behavior can be configured so the player does not have to micro-manage their units. For example automatically engaging an enemy units under certain conditions or prioritizing what target to shoot first based on user-defined criteria.