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
The following is a proposal for a computer wargame delivered over the internet and playable in a web browser.  The NextGen Wargame (NGW) is a game designed to be a tool for learning tactics.  It provides an operational enviornment where the enemy, terrain, and weather all have an affect.  

In most military learning institutions more emphasis is place on planning.  Students are given a situation and given a map and are expected to create an operations order (OPORD), course of action (COA), and a map overlay with the appropriate operational graphics.  This is called a Tactical Decision Exercise (TDE).  

In some cases the student gets to execute their plan but in most situations that's not possible due the lack of time.  For example a typical class at West Point is around 16 students and last for 45 minutes.  To exexute a mission manually you need a facilitator who can resolve combat, movement, spotting, and other tasks all in a 45 minute class.  It's difficult to do this for one cadet much less 16.  The solution is to automate the process using a game.

The NGW serves as the execution component and provides an automated "umpire" that is consistent in its rulings and can quickly perform game functions.  In other words it knows the rules and applies them the same every time.  

### Overview
NGW is a wargame where the player assumes the role of a military commander.  They could be a platoon, company, or battalion commander.  The goal is to successfully accomplish the scenarios mission objectives.  Ideally the player would use the plan the created when they did the TDE, but in all likelihood the player will have to make adjustments to their plan because the enemy, terrain, and weather all have an affect.

Prior to the mission the player is given some information on the mission, enemy, terrain, and time.  If they are playing a scenario that corresponds to their TDE then they already have the information and know the mission objectives.  Other wise they will need to do some planning before they start issuing orders.

The entire operation takes place on a 2d military topographic map image, or a custom image.  Player's use the mouse and a toolbar to issue orders to their units or perform game functions like checking line of sight or plotting artillery.  Players must make decisions in the use of their forces and weapon systems, cover and concealment provided by the terrain, and limitations of the weather.  In some scenarios the player may be confronted with an "event" which usually adds some contradiction to the decision making-process or additional friction that is unplanned for.  

The content creator is the person who sets up the scenario and is based on the desired learning outcomes.  For example the focus of the lesson may be on the use of terrain.  The content creator may decide on a map that limits viable routes to the objective to one or two.  This forces the player to make a decision regarding the best route to take.  Additional conflicts can be added by making the "best" route the most dangerous one due to enemy presence.  Or maybe one route provides better cover and concealment and the other may be faster.  No matter what route the player chooses they still need to justify why they made that choice.

There are two ways for the scenario to end.  Either the mission objectives are accomplished or the player's forces are atritted to the point where they can no longer continue to operate.  If the mission objectives are accomplished a quality check is performed to determine how well the mission was conducted.  For example even though the mission objectives were achieved if the player lost too many forces in the process it may be deemed a marginal success.

What makes NGW a powerful tool is the ability to create content that can be tailored to a specific lesson or learning outcomes.

NGW will support single-player and 2-player sessions played over the internet or local area network.  The game is played inside a web browser and does not require installation on a client computer.  


### Setting

**Content Creator**
- Creates the map image and codes terrain.
- Creates the unit data.
- Creates unit icons if necessary.

**Scenario Designer**
- Interviews the instructor to determine the desired learning outcomes.
- Proposes a map and force structure that meets those needs.
- Produces the written products.

In many cases the content creator and scenario designer may be the same person.

### Gameplay
During the planning or setup phase the player may be allowed to reconfigure their forces and reposition them.  This depends on the scenario.  Likewise they may be given additional assets that provide more or special capabilities, for example a dog handler for detecting IEDs, or a bridging asset.  The player determines how that unit be utililized and may prioritize who get its capability.  

## Marketing

## Development


For additional information please read my <a href="post/ngw_concept">concept</a>.

## If you're interested in developing a useful game for the PME market please [contact me](mailto:vincent.taijeron@gmail.com).
