# Devops & Deployments

[![Build Status](https://travis-ci.org/nvtkaszpir/devops-and-deployments.svg?branch=master)](https://travis-ci.org/nvtkaszpir/devops-and-deployments)

## About

This is a (yet-to-be-defined) game for Devops about Deployments ;)

The general idea is to create game somewhat similar to Dungeons & Dragons but
in completely different setup, focusing on current IT Operations challenges.

## Origin

Credits to Michał Pawluk for original name, expressed around
2019-07-19 14:00 in our room at work.

Some suggestions were expressed over IRC @ freenode.

## Project goal

- create usable assets to perform a game, such as:
  - player chart
  - campaign scenarios
  - gameplay - how to play descriptions
  - exploration, interaction, combat
  - game master guidelines
- focus on doing fast-paced and fun-focused gameplay for newbies,
  so don't make it super serious to the letter.

## General ideas

Feel free to add suggestions. This should be later split into separate docs.

- define your character
- the mission is to fulfill successful deployment in given time/money constraint
- game should be rouge like, so the setup is randomly generated at start,
  examples:
  - you inherit legacy system, throw a dice to define how many years ago it
    was installed and not updated
  - you create a new app, throw a dice to define number of dependencies,
    and for each dependency throw if it has breaking dependencies
  - throw a dice to define system complexity, and for each what app stack
    was used, so for example we got system with 6 services, 2 of them in
    Java, 2 in Python, 1 in Go, 1 in PHP
  - throw a dice to decide what operating system you use
  - do you have cloud providers
  - automation tools (if any)

## Sub documents

- [Characters](Characters.md)
- [Campaigns](Campaigns.md)

## TODO

### Technical

- add GitHub issues template
- switch to RST?

### Non-technical

- shorten name, maybe to `d16d`?
  Why `d16d` ? Well, looking at how Kubernetes was abbreviated -
  squeeze 8 chars in kubernetes word and you get k8s - it was quite
  obvious to squeeze `Devops & Deployments` down to `d16d`.
  Also `D&D`  would confuse quite a lot of people, not to mention about legal infringements.

- read about RPG games because ihavenoideawhatamidoing.jpeg
- world map - actually should be a problem to solve, like an area from start to
  end with traps in modern app development (yeah, agile and stuff...)
- explore phase - discovering the problem area, dependencies among issues, tech stack
- interactions - ?
- combat - actually it is just smaller problem solving
- monsters - problems itself (we don't have problems, we have challenges...)
- spells - should be rather just using general skills in solving problems
- loot - if any?
- define game system, suggestions:
  - [d20](https://en.wikipedia.org/wiki/D20_System)
  - [GURPS](https://en.wikipedia.org/wiki/GURPS)
- choose license, probably Open Game License with Open Game Content
- decide if it should be a solo game or coop (also decides time limit):
  - solo - for coffee break - would be much easier to actually script it
  - coop - over the Internet or with your imaginary friends
- game master doc
- mission constraints, something like:
  - time limit
  - budget
  - what defines succesful deployment - in edge cases the fact that FTP
    upload worked is enough :D

## Worth to see

[dungeon_brawl](https://github.com/jness/dungeon_brawl)
This is is insanely awesome, I think it could be used in here!

[Storytelling system](https://en.wikipedia.org/wiki/Storytelling_System)
[dnd tl;dr](https://github.com/Miserlou/dnd-tldr)
