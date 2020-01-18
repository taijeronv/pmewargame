---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NextGen Wargame Proposal"
subtitle: "Easy, useful, and relevant"
summary: ""
authors: [TJ]
tags: []
categories: ["wargames", "games"]
date: 2020-01-02T06:36:02+02:00
lastmod: 2020-01-02T06:36:02+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "Battalion scouts lead Alpha Co. towards two unknown enemy positions."
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
## Game Design
The following is a proposal for a computer wargame delivered over the internet, playable in a web browser.  The NextGen Wargame (NGW) is a game designed to be a tool for learning tactics.  It provides an operational environment where the enemy, terrain, and weather all have an effect.  The game can be played in 1-player or 2-player mode.  2-player mode includes an option to play against each other or cooperatively against the AI.  
git
In most military learning institutions, the emphasis is placed on planning.  Execution isn't ignored but is frequently missed because there is no time or resources to do it.  

One of the tools used is the Tactical Decision Exercise or TDE.  The TDE can be a planning and execution exercise depending on learning outcomes and available time.  At West Point, it was mostly planning, and if there's time, maybe do one or two executions. 

**TDE Workflow:**
1.  The instructor gives the students a mission and map of the area.
2.  The students write an operations order (OPORD), course of action (COA), and draw the appropriate operational graphics on their map.
3.  The instructor grades the assignment, in some cases, may execute one of the cadet's plans.

A typical West Point class is around 16 students and lasts for 45 minutes.  To execute a mission manually, you need an "umpire" who resolves combat, movement, spotting, and other tasks.  It's challenging to do this for one cadet, much less 16.  

The NGW serves as the execution component and provides an automated "umpire" that is consistent in its rulings and can quickly perform game functions.  In other words, it knows the rules and applies them the same every time.  

**Computer Game benefits:**
- The scenario is automatically setup.
- The computer "umpire" always grades the same way no matter what.
- Improves learning by enabling the student to re-play the operation and try different tactics or courses of action.
- The computer is fast.
- Improves student's ability to visualize the operation by showing them how it unfolds.

### Overview
In the NGW, the player assumes the role of a platoon, company, or battalion commander.  The goal is to accomplish the scenarios of mission objectives. 

Before the mission, the player is given some information on the task, enemy, terrain, and time available. The player creates a plan and attempts to execute it in the game.  

The entire operation takes place on a 2d military topographic map image or a custom image.  Player's use the mouse and hotkeys to issue orders to their units or perform game functions like checking line of sight or plotting artillery.  Players must make decisions in the use of their forces and weapon systems, and take into account the effects of terrain and weather.  In some scenarios, the player may be confronted with an "event," which puts the player in a decision-making quandary.  

The scenario designer works closely with the instructor to create a scenario that meets the lessons learning outcomes.  The scenario designer also creates content such as the map, unit data, written products that support the scenario.  In some cases, the content creator could be a different person, for example, in a large organization.

The scenario ends when one side of the other accomplishes their mission or their forces are too weak to continue.

**What makes NGW a powerful tool:**
- Easy to play.
- Easy to setup.
- Easy to create content.
- Easy to tailor decisions to learning outcomes.

### Setting and Roles
NGW is played on a 2d military topographic map image (jpg or png format) or custom image.  The terrain is coded relative to the map, and the two are linked.  

**Operations Environment**
- Enemy combat units such as giinfantry, armor, and artillery.
- The terrain is represented and affects cover and concealment, trafficability. 
- Weather is modeled and may affect spotting range, air operations, and mobility.
- 
**Scenario Designer**
- Interviews the instructor to determine the desired learning outcomes.
- Proposes a map and force structure that meets those needs.
- Produces written products.
- Creates the map image and codes the terrain data.
- Creates the unit data.
- Creates unit icons if necessary.

For example, the focus of the lesson may be on the use of terrain.  The content creator may decide on a map that limits viable routes to the objective of one or two.  This forces the player to make a decision regarding the best route to take.  Additional conflicts can be added by making the "best" route the most dangerous one due to enemy presence.  Or maybe one route provides better cover and concealment, and the other may be faster.  No matter what route the player chooses, they still need to justify why they made that choice.

### Gameplay
The player is presented with a webpage of scenarios.  A brief summary is shown, which helps the player decide which scenario to play.  The player clicks on the desired scenario and is taken to a separate page where the game is loaded along with the relevant scenario data.

Before the game begins, the player has an opportunity to plan and organize their forces.  The player can use the plan they created when they did their TDE, or they can create a new one.  Before the first turn begins, the player issues orders based on their planning.  Once they are satisfied, they press the "Go" button, and the turn executes.  

1.  Before the first turn is executed, the player does some planning, issues orders, and re-organizes their forces.
2.  Once they are satisfied, they press the "Go" button, and the turn executes.
3.  The game engine hereafter referred to as the "umpire" performs game tasks and makes calculations.  The player watches as the action unfolds.
4.  When the turn is complete, the player issues new orders to their units.
5.  Repeat steps 1-4 until the umpire determines a winner.

A "turn" consists of several phases.  Each phase has a pre-determined set of actions that can be performed, provided specific criteria are met.  For example, to conduct direct fire, the firing unit must first spot the enemy unit and have a clear line of sight, the target unit must be in the range of one of the firing units weapon systems.  If these criteria are met, then the direct fire takes place.

The scenario is complete when the player manually ends it, or the umpire determines certain conditions have been met.  For example, the umpire may determine the player has met the mission objectives.  Success conditions are determined by the instructor and input by the scenario designer.  

## Marketing

## Development


## If you're interested in developing a useful game for the PME market please [contact me](mailto:vincent.taijeron@gmail.com).
