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
The following is a proposal for a computer wargame delivered over the internet and playable in a web browser.  The NextGen Wargame (NGW) is a game designed to be a tool for learning tactics.  It provides an operational environment where the enemy, terrain, and weather all have an effect.  

In many military learning institutions the Tactical Decision Exercise or TDE is one of the main tools used to teach tactics.  The TDE is a is simple to setup and can be tailored to meet specific learning outcomes.  In places like West Point and ROTC the TDE has become more of a planning exercise with no opportunity to execute their course of action.  The problem is there is not enough time.

**TDE Workflow:**
1.  The instructor gives the students a mission and map of operations area.
2.  The students write an operations order (OPORD), course of action (COA), and draw the appropriate operational graphics on their map.
3.  The instructor grades the assignment, in some cases, may execute one of the cadet's plans.

A typical West Point class is around 16 students and lasts for 45 minutes.  To execute a mission manually, the instructor must assume the role as "umpire." The umpire performs game functions like resolving combat, movement, spotting, and other tasks, as you can see this takes time.  It's challenging to do this for one cadet, much less 16.  

The NGW is meant to provide a quick and easy way to for a student to execute their plan.  All the student does is issues orders to their units and the program does the rest.

**Computer Umpire:**
- Sets up the scenario.
- Knows all the rules and enforces them the same no matter who is playing.
- Quickly performs game functions.
- Keeps track of everything that takes place in the game.
- Records the game which enables the student to watch a replay of the operation and conduct a detailed analysis of their actions.
- Allows the student to do the mission again and try different tactics or courses of action.
- Improves student's ability to visualize the operation by showing them how it unfolds.

### Overview
The player assumes the role of a platoon, company, or battalion commander.  The goal is to accomplish the scenarios mission objectives. 

Before the game begins, the player is given information regarding the task, friendly forces, enemy, terrain, and time available. The player creates a plan and attempts to execute it in the game.  

The entire operation takes place on a 2d military topographic map image or a custom image.  

Player's use the mouse and hotkeys to issue orders to their units and perform game functions like checking line of sight or plotting artillery.  

Players must decide how to organize their forces and weapon systems and what tasks to assign them.  They must also take into account the effects of the terrain and weather. In some scenarios, the player may be confronted with an "event(s)," which puts the player in a decision-making quandary.  

The scenario designer works closely with the instructor to create a scenario that meets the lessons learning outcomes.  The scenario designer also creates content such as the map, unit data, written products that support the scenario.  

The scenario ends when one side or the other accomplishes their mission or their forces become too weak to continue.  At the end of each turn the computer umpire determines if either condition has been met.

**What makes NGW a powerful tool:**
- Easy to play.
- Easy to setup.
- Easy to create content.
- Easy to tailor decisions to learning outcomes.

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

## Development


## If you're interested in developing a useful game for the PME market please [contact me](mailto:vincent.taijeron@gmail.com).
