# Ideas

## General ideas

- the mission is to fulfill successful challenge in given constraints, for example:
  + time limit
  + budget
  + what defines mission success, for example in edge cases the fact that FTP
    upload worked is enough :D

- if not using campaigns, then game should be rouge like, so the setup is
  randomly generated at start, examples:
  + you inherit legacy system, throw a dice to define how many years ago it
    was installed and not updated
  + you create a new app, throw a dice to define number of dependencies,
    and for each dependency throw if it has breaking dependencies
  + throw a dice to define system complexity, and for each what app stack
    was used, so for example we got system with 6 services, 2 of them in
    Java, 2 in Python, 1 in Go, 1 in PHP
  + throw a dice to decide what operating system you use
  + do you have cloud providers
  + automation tools (if any)

### Conversion of RPG elements

- world map - actually should be a problem to solve, like an area from start to
  end with traps in modern app development (yeah, agile and stuff...)
- explore phase - discovering the problem area, dependencies among issues,
  tech stack, budget
- interactions - ?
- combat - actually it is just problem solving in action!
- monsters - problems itself (we don't have problems, we have challenges...),
  what about allies? also this depends on the stack, so will need to define
  deps (like you have no java problems if you are php-only shop)
- spells - should be rather just using general skills in solving problems
- loot - if any? this is actually just an experience in practice, or buffs for skills

### Game play ideas

- single-player:
  + you are a single user in a team, others are NPC
  + you have a team to manage yourself
- coop:
  + game master + players
  + optionally everyone replaced by NPC so you can play solo
  + shared screen play - something like coop games on tv?

- turn based, optionally round with high time limit (like 1 minute)

- some monsters can show up only in specific locations
- if none of the players has skill to solve problem there should be option
  to spend time/money to call for consultant, roll dice to solve or lower
  points so it is easier to solve?

### Implementation ideas

- interface for game master - sees a bit more with hits about world
- interface for players

- log stream of events and actions + rolls
- player generator - random + manual tweaks if needed
- game world generator
- file based - ability to add/edit monsters/items easily

## Pros and cons of implementations

### Close world

- any IRC bot, web system that has defined input/output
- limited paths of reaching goal
- would create graph of issues to solve
- requires strict definitions of what is possible or not
- 'divine intervention' in dead-end cases would allow to jump to another path
- easier to make it a single player
- usually would be able to start/finish game during coffee break :)

### Open world

- define tools to help game master to create world
- openness allows to do anything bizarre, thinking out of the box,
  like `can I kill one player in a team? yeah, why not!`
- not everyone is eager to play it more than once if too complex
- making it too complex makes game slow - make player cards super simple

## Sub documents

- [Characters](Characters.md)
- [Campaigns](Campaigns.md)
