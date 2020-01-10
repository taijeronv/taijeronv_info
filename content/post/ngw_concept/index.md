---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Talon"
subtitle: "Company through Brigade Operations"
summary: "Wargame designed to be used as an education tool to teach tactics."
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
## Concept statement
Easy to play wargame that provides a dynamic operational environment to
practice tactical decision-making and problem-solving. 

## Genre(s)
Professional Military Wargame

## Target audience
- Students enrolled in a professional military education program like West Point or ROTC. 
- Military instructors who need to provide a complete experiential learning experience. 
- Military professionals who need to maintain a high degree of tactical competence.

## Unique Selling Points
- Practice tactical decision-making and problem-solving.
- Immersive operational enviroment.
- Lightweight simulation model easy to understand.
- Easy to play, user interface designed for people.

## Player Experience and Game POV
Who is the player? What is the setting? What is the fantasy the game grants the
player? What emotions do you want the player to feel? What keeps the player
engaged for the duration of their play?

## Visual and Audio Style
Talon is played on actual military topographic maps or something similar to
google maps. Unit icons represent platoons, squads, or sections using NATO
symbols or vehicle/equipment silhouettes. Battlefield sounds and animations
provide player feedback and alerts them to critical situations.

NGW is not a first-person-shooter or a virtuality simulation with 3d graphics.

## Game World 
The game world is represented by enemy units, terrain, and weather all of which
have an impact on the operation. Units provide capabilities for all the
warfighting functions.

## Monetization
- Subscription via website.
- Custom game setup on a LAN.
  
The game or subscription can be customized based on the needs of the customer.
For example if they need a more detailed combat model, or they want access to
more advanced content. The LAN setup is meant for organizations that do not want
to deal with the internet.

## Technology, and Scope (brief) PC or mobile?
- Meant to be played inside a web browser.
- Delivered over the internet or LAN, operating system does not matter
- Javascript using the [Phaser game library](https://phaser.io/).

## Objectives and Progression
The player begins by choosing a scenario. The scenario contains information
regarding the operation such as the mission, friendly troops available, map,
objectives, and intel reports. The scenario file contains data used by the game
engine for various functions and calculations.

The player plays the game by giving orders to their units like move, attack,
defend. Orders are based on doctrinal tasks.

The player continues playing until they accomplish the mission or their force
has been defeated or neutralized and can no longer operate. The entire game is "recorded" so
the player can study the operation in greater detail.

## Game Systems 
The simulation model is an abstraction of all the warfighting functions and can
be calibrated to produce believable results.

The graphics engine is fairly basic and the animations can be easily handled by
the Phaser framework. NGW is not a 3d game.

A detailed and configurable AI is a critical part of the system. This enables
content creators to develop realistic enemy behavior and provide a challenging
operational environment for the player.

## Interactivity
The user interface is simple and meant to be intuitive. Orders are given by
right-clicking on the unit and selecting the appropriate order. Automated unit
behavior can be configured so the player does not have to micro-manage their
units. For example automatically engaging an enemy units under certain
conditions or prioritizing what target to shoot first based on user-defined
criteria.