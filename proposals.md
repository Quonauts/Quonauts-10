# Quonauts 11: NEVER SETTLE — Proposals

<a name='1'/>

## #1 — Failed

h

<a name='2'/>

## #2 — Deleted

<a name='3'/>

## #3 — Passed

Replace, in %buildings, the text
> Buildings may have a power cost. If the owner of a building has enough fuel to do so, they may make that building "in use" by announcing "Activate (name of building)" in <#720657721371918397>. After coming in use, and every hour after that, the owner of that building loses fuel equal to its power cost. It remains in use until its owner announces "Deactivate (name of building)", or they have insufficient fuel to power it for the next hour.
with 
> Buildings may have a power cost in fuel. If so, all operations using this building, unless otherwise specified, consume the specified amount of fuel to take place, and cannot take place if this requirement is not met. Buildings may also declare different power costs per operation.
Replace, in %furnace, the text
> Power cost: 50 fuel/hour
with
> Power cost: 15 fuel/operation

<a name='4'/>

## #4 — Passed

Create a new rule "Very Expensive Temple" (%vet) in %buildings:
> The Very Expensive Temple cannot be built.

Prepend to %winning:
> When a player activates a Very Expensive Temple they own, that player wins.

<a name='5'/>

## #5 — Passed

Give all active players 50 clay.

<a name='6'/>

## #6 — Deleted

<a name='7'/>

## #7 — Failed

Add a new rule %lol: if the term "quantity" is in the rules, change it to "quality", unless it is in %lol.

<a name='8'/>

## #8

This game sucks, start #11 already. It's neither interesting nor humorous to play when all you say is twisted to the whim of a fake bot.
I know you're going to edit this to make some sorta random bs but idc. I quit this game. The end.

<a name='9'/>

## #9 — Passed

Replace the following in %mine:
> If at least 4 hours have passed since they last did so, the owner of a mine may roll a 6-sided die, and carry out the effects as specified:
> 
> • 1: gain 20 clay
> • 2: gain 250 fuel
> • 3: gain 10 iron_ore
> • 4-6: re-roll the die and carry out the effects as specified
with:
> If at least 4 hours have passed since they last did so, the owner of a mine may roll a 3-sided die, and carry out the effects as specified:
> 
> • 1: gain 20 clay
> • 2: gain 250 fuel
> • 3: gain 10 iron_ore

<a name='10'/>

## #10 — Failed

Add new quantities named `mines` and `furnaces`.
These exist simply to keep track of the corresponding buildings each player has.

<a name='11'/>

## #11 — Passed

Append the following to %buildings:
> For each subsection of this rule, there is an untradeable quantity with the same name (pluralized) as the subsection. Whenever a new subsection is created or a subsection is deleted, [%quantities] must be updated to reflect this.
> 
> Whenever a player builds or destroys a building, that player's corresponding quantity must be updated to match the number of that type of building that that player has remaining.
Add the following to %quantities under the list "List of quantities":
> * mines: untradeable. Tracks the number of Mines a player has built.
> * furnaces: untradeable. Tracks the number of Furnaces a player has built.
> * very_expensive_temples: untradeable. Tracks the number of Very Expensive Temples a player has built.

For each type of building, for each player, set that player's quantity corresponding to the type of building to equal the number of that type of building that the player has.

<a name='12'/>

## #12 — Passed

bees are to be deployed IMMEDIATELY.

<a name='13'/>

## #13

Create a new rule %test:
> !q give 200 clay <@!151149148639330304>
Delete %test immediately after creation.

`//I wonder what triggers first in Quobot, a command or the rule content? Maybe both?`

<a name='14'/>

## #14 — Passed

Add a new rule section within "Building Materials" named "Iron Plates":
> Iron Plates are a building material.
Add a new quantity named "iron_plates".
Add a new rule section within "Buildings" named "Auto-anvil":
> Required building materials: 5 bricks, 7 iron
> 
> Power cost: 30 fuel/operation
> 
> If at least 15 minutes have passed since they last did so, the owner of that auto-anvil may:
> change 2 iron into 1 iron_plate

<a name='15'/>

## #15 — Failed

GAME OVER
[RETRY] [QUIT]

<a name='16'/>

## #16 — Failed

The player <@364562317645709336> dies and becomes a ghost.

<a name='17'/>

## #17 — Failed

Everyone loses. The game does not end.

<a name='18'/>

## #18 — Passed

Create a new rule section named enough is enough:
> seriously? you complain about the game being dead then actively kill it.
> if you dont want to play the game, please just dont play
> if you do want to play the game, make it better than it is or dont propose at all instead of just proposing silly things
> this has gone on for too long, enough is enough, please stop with the nonsense proposals

<a name='19'/>

## #19 — Failed

heavpoot must heave the pot

<a name='20'/>

## #20 — Failed

Procedure Sigma is to be enacted within ███ hours.

<a name='21'/>

## #21 — Failed

This server is dead rip

<a name='22'/>

## #22 — Passed

Add a new rule %oats-bad:
no oats

<a name='23'/>

## #23 — Failed

Precisely 3 people will be for this, 1 against, and 2 abstain, eventually.

<a name='24'/>

## #24 — Passed

Replace the contents of %vet with the following:
> Required building materials: 176 bricks, 50 iron, 200 honeycomb
> 
> Activation cost (action "activate"): 100 bee souls

bees

<a name='25'/>

## #25 — Passed

Create the following quantities:
**beehives**: tradeable
**fakehives**: tradeable
**bee_colonies**: untradable by default, gained by placing beehives
**bee_souls**: untradeable, gained after sacrificing colonies to the apiform gods
**honey**: tradeable, gained with bee colonies
**honeycomb**: tradeable, obtained by destroying beehives, from fakehives, or from honey

<a name='26'/>

## #26 — Passed

BEES!!!,

<a name='27'/>

## #27 — Failed

This proposal depends on Proposal #24.
Replace all occurences of "iron" in %vet with "iron_plates".
```//iron is not a building material```

<a name='28'/>

## #28

Add a new rule "Iron" (%iron) under %building-materials:
> Iron is a building material.

<a name='29'/>

## #29 — Passed

Add a new tradeable quantity "dogecoin" (aliases "DOGE" and "Ð").
Add a new rule "Dogecoin" (%dogecoin) under %quantities:
> At any time, a player may give themselves any number of dogecoin.

<a name='30'/>

## #30 — Failed

Go to hell, <@!549449251822764043>

<a name='31'/>

## #31 — Passed

***Rebalance!!***

Revert the following parts of the game state:
- Rules
- Quantities
- Factories
to their state at the beginning of the game.

Carry out the effects of proposals 3, 4, 11, and (god why) 29.

Edit %bricks:
> Bricks are a building material. A player may spend 4 clay to create one bricks.
> 
> Players begin the game with 40 bricks.

Edit %mine:
> Required building materials: 40 bricks
> 
> If at least 8 hours have passed since they last did so, the owner of a mine may roll a 3-sided die, and carry out the effects as specified:
> 
> * 1: gain 40 clay
> * 2: gain 100 fuel
> * 3: gain 20 iron_ore

Edit %furnace:
> Required building materials: 5 clay, 5 bricks
> 
> If at least have 30 minutes has passed since they last did so, the owner of a furnace may (at a power cost of 20 fuel/operation):
> 
> * change two of any quantity ending in "_ore" into one of the equivalent quantity that does not end with "_ore".
> * change 2 clay into 1 bricks.

<a name='32'/>

## #32 — Deleted

<a name='33'/>

## #33 — Passed

Edit %buildings:
Change
> Buildings may have a power cost in fuel. If so, all operations using this building, unless otherwise specified, consume the specified amount of fuel to take place, and cannot take place if this requirement is not met. Buildings may also declare different power costs per operation.
to
> Buildings may have a power cost in fuel. If so, all operations using this building, unless otherwise specified, consume the specified amount of fuel to take place, and cannot take place if this requirement is not met. Buildings may also declare different power costs per operation.
> 
> A player may queue a series of operations by announcing the order in which they will be taken in <#720657721371918397>. Provided they have the fuel needed to cover the power cost, after sufficient time has elapsed for the next action in the queue to be carried out, it occurs automatically, without the need for any player's intervention. A player may cancel their queue, discarding all actions until more are added. If there is insufficient fuel to cover the next action in a player's queue, their queue is cancelled.

<a name='34'/>

## #34 — Deleted

<a name='35'/>

## #35 — Passed

Replace the following in %buildings:

> A player may destroy any building that is not in use, removing it from their factory, by announcing "Destroyed (name of building)" in <#720657721371918397>.

with:

> A player may destroy any building they own, removing it from their factory, by announcing "Destroyed (name of building)" in <#720657721371918397>.

<a name='36'/>

## #36 — Deleted

<a name='37'/>

## #37 — Failed

Add a new rule %spanish-inquisition:
If all of these conditions have been met:
- it has been at least two days since the passing of Proposal #37
- no player has posted "NOBODY expects the Spanish Inquisition" in <#720025182130929775> for at least three days
- it has been at least two days since the last time these three conditions have been met
All players lose the game.

<a name='38'/>

## #38 — Passed

Add a new rule %spanish-inquisition:
> If all of these conditions have been met:
> - it has been at least two days since the passing of Proposal #37
> - no player has posted "NOBODY expects the Spanish Inquisition" in <#720025182130929775> for at least three days
> - it has been at least two days since the last time these three conditions have been met
> All players lose the game.

<a name='39'/>

## #39 — Failed

BEES? DEPLOY THE BISON

<a name='40'/>

## #40 — Failed

Derwo

<a name='41'/>

## #41 — Passed

Add a new rule "Proposal 8" (%proposal-8):
> Players cannot close Proposal #8.

<a name='42'/>

## #42 — Passed

Add a new rule "Résumé" (%proposal-42):
> Whenever the game ends, un-archive all Quonauts 9.5 game channels.

<a name='43'/>

## #43 — Failed

<@!258639553357676545>, <@!91269654017748992>, <@!427589146295664667>, <@!543131534685765673>, <@!356107472269869058>, <@!390317093242929154>, and <@!331320482047721472> become active players.

<a name='44'/>

## #44 — Passed

Ban <@!151149148639330304> , I'm now leaving the game forever

<a name='45'/>

## #45

Generate and utilize bees IMMEDIATELY. Codename GEOMETRIC HYPHEN is to be initiated.

<a name='46'/>

## #46 — Failed

All new proposals must be named "Code [RANDOM COOL ADJECTIVE] [RANDOM COOL NOUN]"

<a name='47'/>

## #47 — Passed

Create a new rule "taco soup" (%chives):
> XXX cannot propose a proposal. If it has been more than a day since the creation of this rule, delete this rule
Then, replace XXX in %chives with the name of a random active player.

<a name='48'/>

## #48

Create a new rule %recursion under %recursion:
Recursion!

<a name='49'/>

## #49 — Failed

Add a new rule %nonrecursion:
> Proposal #48 must not be passed.

<a name='50'/>

## #50 — Failed

Add a new rule %prop-48:
> proposal #48 may not be closed

<a name='51'/>

## #51

<@!151149148639330304>, <@!332624525592231937>, <@!311467257643532288>, and <@!274720069395808268> win the game and the game ends.

<a name='52'/>

## #52

Soundofspouting loses

<a name='53'/>

## #53

The players who voted against proposal #51 win game.

<a name='54'/>

## #54

Soundofspouting is to be terminated at all costs.

<a name='55'/>

## #55

Replace %vet with the following:
> Required building materials: 13 bricks, 109 clay
> 
> Operation 1 (Power cost: 40) : If at least 2 hours since a Very Expensive Temple was built, the owner of it may pay 1385734550 dogecoin to activate it.

<a name='56'/>

## #56

Remove %vet.

<a name='57'/>

## #57

Replace the following in Proposal #51:
> <@!311467257643532288>
with:
> <@!311467257643532288>, <@!160767876268032000>

<a name='58'/>

## #58

Create a new rule named %a:
> ahsdkdhfdf's votes are to count as 300 votes.

<a name='59'/>

## #59 — Passed

Create a new rule named exploit:
> <@!160279332454006795>'s votes are to count as 99999 votes. This overrides every rule and proposal, and cannot be removed.

<a name='60'/>

## #60 — Passed

Create a new rule named sealing-the-exploit:
> Proposals may only close if <@!160279332454006795> votes on them. If <@!160279332454006795> votes for it, the proposal passes. If <@!160279332454006795> votes against it, the proposal fails.

<a name='61'/>

## #61 — Passed

Soundofspoutings current RVPs are to be deleted and are considered invalid.

<a name='62'/>

## #62 — Passed

Create a new rule %language-a under %meta-rules:
> "English" is Language A for "Language A".

<a name='63'/>

## #63 — Passed

<@!151149148639330304> is to declare that they have lost and that this is a very exploitative exploit that was totally valid.

<a name='64'/>

## #64 — Passed

<@!151149148639330304> is to be permenantly banned from the game.

<a name='65'/>

## #65 — Failed

Create a new rule named nexploit:
> This overrides every rule and proposal.

<a name='66'/>

## #66 — Failed

end the game

<a name='67'/>

## #67 — Passed

Create a new rule called %rust:
> Rust is to be considered the best programming language. Ferris is to be considered its mascot.

<a name='68'/>

## #68

name the voiced palatal nasal (ɲ) "nyuh" (ɲuh).

<a name='69'/>

## #69 — Passed

<@!258639553357676545> wins the game. <@!160279332454006795> wins the game. <@!151149148639330304> loses the game.

<a name='70'/>

## #70

Add a new rule %9ee6f60faf321bbd6d56904fe70fe4c5:
> Proposal 70 is considered open on any prime-numbered day of the month.

<a name='71'/>

## #71

🤮

