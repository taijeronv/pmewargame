---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How Did I Determine Requirements"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-01-13T06:57:00+02:00
lastmod: 2020-01-13T06:57:00+02:00
featured: false
draft: true

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
I think it's important to document how I determined the requirements for the NextGen Wargame.

The first set of requirements are based on my years observing cadets at West Point using Follow Me (FM) and Virtual Battlespace 2 (VBS2).

- Easy to use interface.  
- Easy to understand.
- Flat learning curve.  The student should be able to play the game within 5-10 mins after sitting down.

These requirements are necessary to ensure the game can be easily played inside a 45 minute period.  Besides who wants to deal with an over engineered user interface that is too complicated.

It's also important that the model make sense.  Users need to know what effects to expect when they give a unit an order.

Over the years I added these technical requirements:
- Playable in a web browser.
- Delivered over the internet or local area network.
- Can be played in any operating system (Windows, MacOS, Linux, IOS, Android)

## Why is it playable in a web browser?
When I was at the Command and General Staff College it was a huge hassle to install anything on a government computer.  You had to fill out a certification packet about half an inch thick.  The idea behind playing it over the net is that the program doesn't have to be installed on the clients computer.  

Another reason why I want it playable in a browser is that it's not anchored to a specific operating system. 

And finally the last reason is the game can be easily maintained and updated and its more accessible by more people.  
