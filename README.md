<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project: Surreal EscaPY

## Overview

If you know [Zork I: The Great Underground Empire](https://en.wikipedia.org/wiki/Zork) ...congrats (wow, you must be older than time!). Text-based adventure games like that, have inspired gaming since 1977. Our goal for the first team project ([Aris Goulas](https://github.com/ArisGoulas), [Letícia De Marchi](https://github.com/leticiademarchiferreira), [Matheus Freire](https://github.com/MatheusFreir) was to use our freshly-acquired Python programming skills, in order to develop the game design of a classic game - Escape Room further. We therefore present you with Surreal EscaPY!

---

## Game Design

Our development consists of 3 (and a half) features:
- Environment customization: surreal nightmare - personalization of the experience (MVP)
- "check" action addition - gameplay (towards a future inventory feature)
- Map layout differentiation - replayability (towards a future random map feature)
- Player name & Timer - gameplay (towards a future scoring feature)

### Game Map

![Game Map](escape-room-plan.jpg)

### Game Narratives

#### Game Room

You wake up on a couch and find yourself in a strange house with no windows which you have never been to before. You don't remember why you are here and what had happened before. You feel some unknown danger is approaching and you must get out of the house, NOW!

You are now in game room.

What would you like to do?

You explore the room. This is Game Room. You find couch, piano, and Door A.

You examine couch. There isn't anything interesting about it.

You examine Door A. It is locked but you don't have the key.

You examine piano. You find key for Door A.

You examine Door A. Your unlock it with a key you have.

Do you want to go to the next room?

#### Bedroom 1

You are now in Bedroom 1.

What would you like to do?

You explore the room. This is Bedroom 1. You find queen bed, Door A, Door B, and Door C.

You examine queen bed. You find key for Door B.

You examine Door C. It is locked but you don't have the key.

You examine Door B. Your unlock it with a key you have.

Do you want to go to the next room?

#### Bedroom 2

You are now in Bedroom 2.

What would you like to do?

You explore the room. This is Bedroom 2. You find double bed, dresser, and Door B.

You examine double bed. You find key for Door C.

You examine dresser. You find key for Door D.

You examine Door B. Your unlock it with a key you have.

Do you want to go to the next room?

#### Bedroom 1

You are now in Bedroom 1.

What would you like to do?

You examine Door C. Your unlock it with a key you have.

Do you want to go to the next room?

#### Living Room

You are now in Living Room.

What would you like to do?

You explore the room. This is Living Room. You find dining table, Door C, and Door D.

You examine Door D. Your unlock it with a key you have.

Do you want to go to the next room?

#### Outside

Congrats! You escaped the room!

---

## Getting Started

Overwhelmed and don't know where to start? This is a tough challenge we know. But don't worry. We have included a working example for you to reference in which only 1 room (game room) is included. Read the example and make sure you understand it. Then you can expand on top of the example to code the rest of the rooms.

The provided example is just a Minimal Viable Product (MVP). It is fully functional but not bullet proof. You should be aware of its limitations while you are working and try to make your final product as robust as possible.

## Technical Requirements

* Use Python lists and dictionaries to define the rooms, items, and relations of them.

* Use a Python dictionary to store the game state. Update the state dictionary when progresses are made such as a key is collected.

* Use Python functions to play the game. Don't use procedural code.

* After completing each game action, call the next function to continue playing until the winning condition is reached.

* The winning condition is for the player to successfully make to the "Outside" room. When this happens, congrat the player and end the game.

## Necessary Deliverables

The following deliverables should be pushed to your Github repo.

* `main.ipynb` that contains your solution.

## Suggested Ways to Get Started

1. Start Jupyter Notebook from this lab directory.

1. Launch `sample-code.ipynb` and read through the file. Also execute the code and play the game. Make sure you understand what each line of the codes does.

1. Create `main.ipynb` and copy the codes from `sample-code.ipynb`. Expand the code following the example to create Bedroom 1.

1. Test the game with Game Room and Bedroom 1. Make sure everything works then work on Bedroom 2 then Living Room.

1. Test the whole game. Try to make all kinds of inputs to make sure your game is rock solid and will not break.
