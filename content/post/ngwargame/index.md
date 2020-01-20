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

In many military learning institutions, the Tactical Decision Exercise or TDE is one of the main tools used to teach tactics.  The TDE is simple to set up and can be tailored to meet specific learning outcomes.  In places like West Point and ROTC, the TDE has become more of a planning exercise because there is not enough time to include the execution piece.  

**TDE Workflow:**
1.  The instructor gives the students a mission and a map of the operations area.
2.  The students write an operations order (OPORD), plan a course of action (COA), and draw the appropriate operational graphics on the map.
3.  The instructor grades the assignment.

A typical West Point class is around 16 students and lasts for 45 minutes.  To execute a mission manually, the instructor assumes the role of "umpire." The umpire performs game functions like resolving combat, movement, spotting, and other tasks. As you can see, this takes time.  It's challenging to do this for one cadet, let alone 16.  

The NGW is meant to provide a quick and easy way for a student to execute their plan.  All the student does is issue orders to their units, and the program does the rest.

**Computer Umpire:**
- Sets up the scenario.
- Knows and enforces all the rules.
- Quickly performs game functions.
- Keeps track of everything that takes place in the game.
- Records the game so the student can review it in more detail later.
- It allows the student to practice the same mission as many times as they like allowing them to try different tactics or courses of action.
- Improves student's ability to visualize the operation by showing them how it unfolds.

### Overview
The NextGen Wargame puts the player in the role of a platoon, company, or battalion commander.  

Before the game begins, the player is given information regarding the task, friendly forces, enemy, terrain, and time available. The player creates a course of action and attempts to execute it in the game.  To win, they must accomplish the scenario's mission objectives.

The entire operation takes place on a 2d image that represents a military topographic map.  The map is produced using a commercial program like Adobe Illustrator/Photoshop.  

Player's use the mouse and keyboard commands to issue orders to their units.  They must decide how to organize their forces, employ weapon systems, and assign tasks to their units while taking into account the effects of the terrain and weather. 

Events can be added to a scenario to force students into specific decision-making situations.  For example, an event may be triggered whenever one of the player's units enters a specific location.  

A Scenario Designer works closely with the instructor to create a scenario that meets the lessons learning outcomes.  The scenario designer also creates content like the map, unit data, and the instructor's guide.  

The game ends when one side or the other accomplishes their mission or their forces become too weak to continue.  At the end of each turn, the computer umpire determines if either condition has been met.

### Gameplay
The player is presented with a webpage with a list of scenarios.  Each scenario has a brief summary giving the player an idea of what it is about. 

1.  The player decides on a scenario to play and clicks the link.  Another page opens with an instance of the game and more detailed information regarding the situation.
2.  The player does some planning, issues orders, and organizes their forces.  In some scenarios, they may be allowed to reposition their units.
3.  Once they are satisfied, they press the "Go" button, and the turn executes.
4.  The computer umpire or "umpire" performs game tasks, makes calculations, and executes the turn.
5.  The player is notified that the turn is complete and presses the play button to see what happened.  They can spend as much time as they like reviewing the results of the turn.
6.  The player issues new orders to their units, and presses "Go" to execute another turn.
7.  Repeat steps 1-4 until the umpire determines a winner.

A "turn" consists of two or three phases and represents a variable amount of actual time anywhere from 5-15 minutes.  Each phase has a pre-determined set of actions that can be performed, provided specific criteria are met.  

The scenario is complete when the player chooses to surrender, or the computer umpire determines certain conditions have been met.  

## Content
The NextGen Wargame content is fairly easy to create using 3rd party programs like Photoshop and a simple text editor.

**Maps**  
> insert map image here

Maps are simple 2d images in jpeg or png format.  The image itself has no function in the game other than to provide a visual reference for the player.  The terrain is coded as an overlay on top of the image and is saved as a separate file.  The game engine or computer umpire uses this data to perform game functions like determining line of sight, movement, cover, and concealment functions.

The scenario designer has the option of creating a map image from scratch, or they can use an existing image downloaded from the internet.  The only restriction is on the format of the image (jpg or png).

A third-party program such as Adobe Photoshop and Illustrator is the easiest way to create a map image from scratch.  Freeware programs like Gimp and Inkscape can be used instead of the Adobe products.

In future versions of the game, the intent is to provide the option of using an online cloud-based mapping solution like Google Maps or Openstreet.

**Unit Icons**  
> insert icon image here

Unit icons represent military platoons, squads, and sections, which are the playing pieces.  They are created using the same programs used to make maps.  The customer can choose to use their own icons or any icon set as long as it meets the specifications for the image format.  

**Scenarios**  
Scenarios consist of a map and terrain file, unit icons, and unit data.  It is packaged as a single file and loaded on-demand whenever the player chooses it.  Scenarios also consist of written content that orients the player to the mission objectives, and reports regarding the terrain and enemy.  The written content can be as detailed or vague, depending on the learning outcomes.

**Replays**  
Replays are scenarios that have been "played"  and recorded so they can be reviewed.  This is one of the easiest and most effective ways to use NGW, and it does not require the instructor or student to know how to play the game. 

The idea is to review the replay and conduct an analysis of how the operation was executed.  The player simply watches and takes notes.  The beauty of this method is that the instructor and scenario designer control what's taking place in the game.  In other words, they can make decisions that the student can analyze.  Facilitating such an exercise is easy because the instructor already knows where the teaching points take place.  

Once the replay has been recorded, the scenario designer and instructor collaborate on creating the instructor's notes.  The instructor's notes list the decisions and when they occur in the game and offer up facilitation points.  This is where the instructor drives the discussion.

## Marketing
The NextGen Wargame is consist of three products:

- The basic game includes five basic scenarios.  
- Premium content, scenarios that are complete lessons with supporting documentation.
- Services like creating custom content, or installing and maintaining the game on a local area network.

Customers can purchase an annual subscription that is tailored to their needs.  For example, they may need specialized content to support their program of instruction.  A basic subscription comes with five scenarios with one instructor's guide that covers all five situations.

Subscriptions are the easiest way to "distribute" the game and have the broadest reach in terms of customers.  It does not require installation on client computers and can easily be maintained and updated from the server-side location.  

It is also possible to install the program on a local area network, but this setup requires additional costs.

## Development
Initial development can be accomplished with one project manager and two Javascript programmers.  Note one of the programmers must double as a Frontend Developer responsible for developing the website.

The art in NGW is minimal and can be contracted out to a third party or created in-house.  

When the project enters full development, the team should add a dedicated Frontend Developer, Graphics Artist/Content Creator.  

Full Development
1 x Project Manager who also serves as the military subject matter expert and game designer
2 x Javascript programmers
1 x Frontend Developer
1 x Graphics Artist/Content Creator

Note the sound and animations requirements are quite minimal and do not require specialists.

**Timeline**  
- 3-6 Months for a minimal a fully playable demo.
- 6 additional months for a fully developed game.

Note the game model is not that complicated.

<a href="post/ngwargame">NGW Proposal</a>
<a href="post/ngw_concept">NGW Proposal</a>

## If you're interested in developing a useful game for the PME market please [contact me](mailto:vincent.taijeron@gmail.com).
