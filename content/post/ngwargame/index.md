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

In many military learning institutions, the Tactical Decision Exercise or TDE is one of the main tools used to teach tactics.  The TDE is simple to set up and can be tailored to meet specific learning outcomes.  In places like West Point and ROTC, the TDE has become more of a planning exercise with no execution component.  The problem with including an execution piece is time, there is not enough of it.

**TDE Workflow:**
1.  The instructor gives the students a mission and a map of the operations area.
2.  The students write an operations order (OPORD), plan a course of action (COA), and draw the appropriate operational graphics on the map.
3.  The instructor grades the assignment.

A typical West Point class is around 16 students and lasts for 45 minutes.  To execute a mission manually, the instructor assumes the role of "umpire." The umpire performs game functions like resolving combat, movement, spotting, and other tasks. As you can see, this takes time.  It's challenging to do this for one cadet, let alone 16.  

The NGW is meant to provide a quick and easy way for a student to execute their plan.  All the student does is issue orders to their units, and the program does the rest.  When you add the execution piece, the quality of the instruction goes up.  Cadets get the complete experience of planning and execution.

**Computer Umpire:**
- Sets up the scenario.
- Knows and enforces all the rules.
- Quickly performs game functions.
- Keeps track of everything that takes place in the game.
- Records the game so the student can review it in more detail later.
- It allows the student to practice the same mission as many times as they like allowing them to try different tactics or courses of action.
- Improves student's ability to visualize the operation by showing them how it unfolds.

### Overview
The NextGen Wargame outs the player in the role of a platoon, company, or battalion commander.  

The player must accomplish the scenario's mission objectives to win.

Before the game begins, the player is given information regarding the task, friendly forces, enemy, terrain, and time available. The player creates a course of action and attempts to execute it in the game.  

The entire operation takes place on a 2d image that represents a military topographic map.  The map is produced using a commercial program like Adobe Illustrator/Photoshop.  

Player's use the mouse and keyboard commands to issue orders to their units and perform game functions like checking line of sight or plotting artillery.  

Players must decide how to organize their forces, employ weapon systems, and assign them tasks.  They must also take into account the effects of the terrain and weather. In some scenarios, the player may be confronted with an "event(s)," which puts then in a decision-making quandary.  Events are triggered by specific criteria like the location of a unit, or a unit's actions.  

Events are important because it forces the player to make a decision.

The scenario designer works closely with the instructor to create a scenario that meets the lessons learning outcomes.  The scenario designer also creates content such as the map, unit data, scenario notes, and the instructor's guide.  

The game ends when one side or the other accomplish their mission or their forces become too weak to continue.  At the end of each turn, the computer umpire determines if either condition has been met.

### Gameplay
The player is presented with a webpage with a list of scenarios.  Each scenario has a brief summary giving the player an idea of what it is about. 

1.  The player decides on a scenario to play and clicks the link.  Another page opens with an instance of the game and more detailed information regarding the situation.
2.  The player does some planning, issues orders, and organizes their forces.  In some scenarios, they may be allowed to reposition their units.
3.  Once they are satisfied, they press the "Go" button, and the turn executes.
4.  The game engine hereafter referred to as the "umpire" performs game tasks and makes calculations and executes the turn.
5.  The player is notified that the turn is complete and presses the play button to see what happened.  They can spend as much time as they like reviewing the results of the turn.
6.  The player issues new orders to their units, and presses "Go" to execute another turn.
7.  Repeat steps 1-4 until the umpire determines a winner.

A "turn" consists of several phases and represents a variable amount of actual time anywhere from 5-15 minutes.  Each phase has a pre-determined set of actions that can be performed, provided specific criteria are met.  

The scenario is complete when the player chooses to surrender, or the umpire determines certain conditions have been met.  

## Marketing
The NextGen Wargame is really three products:

- Access to the game and 10-15 basic scenarios.  
- Premium content consist of scenarios that are really complete lessons with supporting documents.
- Teaching organizations how to use the game, developing custom content, or maintaining the program if installed locally.

The easiest way to market the program is to use a subscription service.  Customers can buy annual subscriptions which gives them access to specific content depending on what package they purchase.  The primary audience for NGW is learning institutions with a professional military education program.  

The program can be installed on a local area network but this setup would incur additional maintenance costs.  It is not hard but does take additional time and effort maintain and update.

## Development
Initial development can be accomplished with a skeleton crew of one project manager, and two programmers, and one frontend developer.  

The art in NGW is minimal and can be contracted out initially.  Full development would require a dedicated graphics artist mainly to create map images.  All animations can be handled by the Phaser framework and does not require an animation artist.  One or two dedicated content creators may be required depending on the demand for content.

Music can be contracted out as well as the sound effects which can be purchased separately.

<a href="post/ngwargame">NGW Proposal</a>
<a href="post/ngw_concept">NGW Proposal</a>

## If you're interested in developing a useful game for the PME market please [contact me](mailto:vincent.taijeron@gmail.com).
