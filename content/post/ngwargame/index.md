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
The following is a proposal for a computer wargame playable over the internet inside a web browser.  The NextGen Wargame (NGW) is a game designed to be a tool for learning tactics.  It provides an operational environment where the enemy, terrain, and weather all have an effect and enables the player to practice making decisions in a tactical environment.

In many military learning institutions the Tactical Decision Exercise or TDE is one of the main tools used to teach tactics.  The TDE is simple to setup and can be tailored to meet specific learning outcomes.  In places like West Point and ROTC the TDE has become more of a planning exercise with no execution component.  It is not that they think planning is more important, they simply do not have the time to do any execution.

**TDE Workflow:**
1.  The instructor gives the students a mission and a map of the operations area.
2.  The students write an operations order (OPORD), plan a course of action (COA), and draw the appropriate operational graphics on the map.
3.  The instructor grades the assignment.

A typical West Point class is around 16 students and lasts for 45 minutes.  To execute a mission manually, the instructor must assume the role of "umpire." The umpire performs game functions like resolving combat, movement, spotting, and other tasks, as you can imagine this takes time.  It's challenging to do this for one cadet, let alone 16.

The NGW is meant to provide a quick and easy way to for a student to execute their plan.  All the student does is issue orders to their units and the program does the rest.  

{{% alert note %}}
NGW is designed to provide a quick and easy execution component that supplements the paper-based TDE.  It is NOT meant to replace it.
{{% /alert %}}

**Computer Umpire**
The "umpire" is the heart of the game and provides a number of benefits:
- Sets up the scenario.
- Knows and enforces all the rules.
- Quickly performs game functions.
- Keeps track of everything that takes place in the game.
- Records the game so the student can review it in more detail later.
- Provide an opporutnity for "quality practice by allowing the student to do the same mission as many times as they like so they can experiment with different tactics or courses of action.

### Overview
The NextGen Wargame puts the player in the role of a platoon, company, or battalion commander.  

To win, the player must accomplish the scenarios mission objectives.

Before the game begins, the player is given information regarding the task, friendly forces, enemy, terrain, and time available. The player creates a course of action and attempts to execute it in the game.  

The entire operation takes place on a 2d image that represents a military topographic map.  The map is produced using a commercial program like Adobe Illustrator/Photoshop.  

Player's issue orders to their units using the mouse and keyboard-commands.

Players must decide how to organize their forces, employ weapon systems, and assign tasks to their units.  They must also take into account the effects of the terrain and weather. In some scenarios, the player may be confronted with an "event(s)," which puts then in a decision-making quandary.  Events are triggered by certain criteria like the location of a unit, or a unit's actions.  

Events are important because it enables the instructor to add additional decision-making opportunities that may not take place naturally in the course of the game.

The scenario designer works closely with the instructor to create a scenario that meets the lessons learning outcomes.  The scenario designer also creates content such as the map, unit data, scenario notes, and the instructors guide.  

The scenario ends when one side or the other accomplishes their mission or their forces become too weak to continue.  At the end of each turn the computer umpire determines if either condition has been met.

**What makes NGW a powerful tool:**
- Easy to play.
- Easy to setup.
- Easy to create content.
- Easy to tailor decisions to learning outcomes.

### Gameplay
The player is presented with a webpage with a list of  scenarios.  Each scenario has a brief summary giving the player an idea of what it is about. 

1.  Before the first turn is executed, the player does some planning, issues orders, and re-organizes their forces.
2.  Once they are satisfied, they press the "Go" button, and the turn executes.
3.  The game engine hereafter referred to as the "umpire" performs game tasks and makes calculations.  The player watches as the action unfolds.
4.  When the turn is complete, the player issues new orders to their units.
5.  Repeat steps 1-4 until the umpire determines a winner.

A "turn" consists of several phases and represents a variable amount of actual time anywhere from 5-15 minutes.  Each phase has a pre-determined set of actions that can be performed, provided specific criteria are met.  

>For example, to conduct direct fire, the firing unit must first spot the enemy unit and have an unblocked line of sight, the target unit must be in  range of one of the firing units weapon systems.  If these criteria are met, then the direct fire takes place.

The scenario is complete when the player manually ends it, or the umpire determines certain conditions have been met.  

>For example, the umpire may determine the player has met the mission objectives.  Success conditions are determined by the instructor and input by the scenario designer.  

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
