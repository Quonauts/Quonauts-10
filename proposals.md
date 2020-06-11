# Quonauts X: Factory Reset — Proposals

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

## #7

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

## #10

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

