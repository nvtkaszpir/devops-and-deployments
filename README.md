# Devops & Deployments

## About

This is a (yet-to-be-defined) game for Devops about Deployments ;)

The general idea is to create game similar to Dungeons & Dragons but
in completely different setup, focusing on current IT Operations challenges.

## Origin

Credits to Michał Pawluk for original name, expressed around
2019-07-19 14:00 in our room at work.

Some suggestions were expressed over IRC @ freenode.

## General ideas

Feel free to add suggestions. This should be later split into separate docs.

- define your character
- the mission is to fulfill succesful deployment in given time/money constraint
- game should be rouge like, so the setup is randomly generated at start,
  examples:
  - you inherit legacy system, throw a dice to define how many years ago it
    was installed and not updated
  - you create a new app, throw a dice to define numbr of dependencies,
    and for each dependency throw if it has breaking deps
  - thorw a dice to define system complexity, and for each what app stack
    was used, so for examle we got system with 6 services, 2 of them in
    java, 2 in python, 1 in gloang, 1 in php
  - throw a dice to decide what operationg system you use
  - do you have cloud providers
  - automation tools (if any)

## TODO

### Technical

- add github issues template
- travis for markdown
- switch to rst?

### Non-technical

- shorten name, maybe to `d16d`?
  Why `d16d` ? Well, looking at how Kubernetes was abbreviated -
  squeeze 8 chars in kubernetes word and you get k8s - it was quite
  obvious to squeeze `Devops & Deployments` down to `d16d`.
  Also `D&D`  would confuse quite a lot of people, not to mention about legal infringements.

- read about RPG games because ihavenoideawhatamidoing.jpeg
- define game system, suggestions:
  - [d20](https://en.wikipedia.org/wiki/D20_System)
  - [GURPS](https://en.wikipedia.org/wiki/GURPS)
- choose license, probably Open Game License with Open Game Content
- decide if it should be a solo game or coop (also decides time limit):
  - solo - for coffee break - would be much easier to actually script it
  - coop - over the Internet or with your imaginary friends
- character attributes
- character skills
- mission constraints, something like:
  - timelimit
  - budget
  - what defines succesful deployment - in edge cases the fact that ftp
    upload worked is enough :D
