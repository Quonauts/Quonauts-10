# Quonauts 11: NEVER SETTLE — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Glossary**](#glossary)
    * [**1.2. Accurcay**](#accuracy)
    * [**1.3. Precedence**](#precedence)
    * [**1.4. Rule violations**](#rule-violations)
    * [**1.5. Timezones**](#timezones)
    * [**1.6. Bots**](#bots)
    * [**1.7. Style conventions**](#style-conventions)
        * [**1.7.1. Content**](#content)
        * [**1.7.2. Headers and tags**](#headers-and-tags)
        * [**1.7.3. Lists**](#lists)
        * [**1.7.4. Formatting**](#formatting)
* [**2. Channels**](#channels)
    * [**2.1. #general**](#general)
    * [**2.2. #proposals**](#proposals)
        * [**2.2.1. Proposal content**](#proposal-content)
            * [**2.2.1.1. Conflict resolution**](#conflict-resolution)
            * [**2.2.1.2. Dependency resolution**](#dependency-resolution)
        * [**2.2.2. Voting on proposals**](#voting-on-proposals)
        * [**2.2.3. Closing proposals**](#closing-proposals)
            * [**2.2.3.1. Passing and failing proposals**](#passing-and-failing-proposals)
        * [**2.2.4. Deleting proposals**](#deleting-proposals)
        * [**2.2.5. Editing proposals**](#editing-proposals)
    * [**2.3. #rules**](#rules)
    * [**2.4. #polls**](#polls)
        * [**2.4.1. Rule violation polls**](#rule-violation-polls)
    * [**2.5. #transactions**](#transactions)
    * [**2.6. #factories**](#factories)
        * [**2.6.1. Building materials**](#building-materials)
            * [**2.6.1.1. Clay**](#clay)
            * [**2.6.1.2. Bricks**](#bricks)
        * [**2.6.2. Buildings**](#buildings)
            * [**2.6.2.1. Mine**](#mine)
            * [**2.6.2.2. Furnace**](#furnace)
            * [**2.6.2.3. Very Expensive Temple**](#vet)
* [**3. Quantities**](#quantities)
    * [**3.1. Trade**](#trade)
    * [**3.2. Dogecoin**](#dogecoin)
* [**4. Winning**](#winning)
* [**5. Proposal 8**](#proposal-8)
* [**6. Résumé**](#proposal-42)
* [**7. Rust**](#rust)

## <a name='meta-rules'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and its subsections. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic governed by these rules.
* **Game Channel**: Any text or voice channel listed under the "Game Channels" category of the Discord server.
* **Game Action**: Any modification of the game state.
* **Game State**: Every current rule; every non-deleted proposal and any votes on it; every poll and any votes on it; every quantity and its values for each player; every player's factory; and every message or reaction in every game channel.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules contained under one header. Unless otherwise specified, this does not include its subsections.
* **Subsection**: A section contained within another another section.
* **Clause**: A single statement in the rules.
* **Player**: Any participant of the game.
* **Active Player**: Any player who has performed a game action in the preceding 72 hours, and is a member of the Discord server.
* **Inactive Player**: Any player who is not an active player.

### <a name='accuracy'/> Accurcay

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they are, rather than their description in this document.

### <a name='precedence'/> Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

* If precedence is specified in the relevant rules and is non-contradictory, follow the instructed precedence.
* The clause which appears last in the rules takes precedence.

### <a name='rule-violations'/> Rule violations

Unless explicitly stated in the rules, all game actions are forbidden.

Any game action that is forbidden (a "rule violation") is considered void and does not modify the game state; the action and its consequences are to be reverted.

### <a name='timezones'/> Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots"; the behaviour of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### <a name='style-conventions'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning. Note that the meaning of other, linked rule sections must not be changed by such an edit.

#### <a name='content'/> Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='headers-and-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### <a name='lists'/> Lists

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### <a name='formatting'/> Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

## <a name='channels'/> Channels

Each subsection of this rule section corresponds to a game channel; as the subsections are created, removed, renamed, or reordered, game channels must be created/removed/renamed/reordered accordingly.

### <a name='general'/> #general

Players may talk freely in the <#720025182130929775> channel.

### <a name='proposals'/> #proposals

Proposals can be made by posting them to the <#720331819530321920> game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed.

#### <a name='proposal-content'/> Proposal content

A proposal must describe one or more actions that make changes to the game rules or otherwise alter the game state.

A proposal must not reference information outside of the game state, or propose a rule that does so.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified.

If a proposal describes the creation of a new rule section, it must specify its title, its content, and should specify its location in relation to an existing rule; if and only if it does not specify a location, then it will be assumed that its location is below all other currently existing rules (this does not apply after the proposal has been enacted).

Any open proposal that does not comply to these rules may be closed as failed at any time.

##### <a name='conflict-resolution'/> Conflict resolution

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

##### <a name='dependency-resolution'/> Dependency resolution

A proposal may state that it depends on other proposals, meaning that proposal will fail if any proposal it depends on fails.

A proposal may also state it is incompatible with other proposals, in which case that proposal will fail if any proposal it is incompatible with passes.

#### <a name='voting-on-proposals'/> Voting on proposals

Each player may cast one vote on each open proposal.

Players may vote in favour of (vote "for") a proposal by reacting to the proposal with 👍, vote against by reacting with 👎, or abstain from voting by reacting with 🤷.

A player may change their vote on an open proposal at any time.

#### <a name='closing-proposals'/> Closing proposals

Any player may close an open proposal if one or more of the following conditions is met:

* The proposal is at least 48 hours (2 days) old.
* All active players have cast a vote or abstained from voting on the proposal, and there are more than 2 active players.
* A majority of active players have voted in favour of or abstained from voting on the proposal, and there are more than 2 active players.
* A majority of active players have voted against or abstained from voting on the proposal, and there are more than 2 active players.

##### <a name='passing-and-failing-proposals'/> Passing and failing proposals

When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails.

The player that authored a proposal may fail it at any time if it is open.

After a proposal passes, the game state and game rules are modified according to it. The player who passed it must carry out the effects of its passing to the best of their ability.

The rules may only change as the result of a proposal passing, legally.

#### <a name='deleting-proposals'/> Deleting proposals

A deleted proposal is closed, but does not pass or fail.

The author of an open proposal may delete it at any time.

#### <a name='editing-proposals'/> Editing proposals

The author of an open proposal may edit it at any time if it has no votes on it other than its author.

The author of an open proposal may edit it to add or remove whitespace and fix typos or grammar mistakes, provided the meaning of the proposal and any dependent proposals remains unchanged. Clarifications or additional details must always be added by a new proposal.

### <a name='rules'/> #rules

The <#720331665666474035> channel contains this rules document.

### <a name='polls'/> #polls

A poll is a means of gathering the opinions of players on an issue. A poll is created by sending a message in the <#720025668460478597> channel, provided a rule permits the poll's creation.

Players may vote on a poll by reacting to it with a certain reaction, as specified in the rule permitting the poll's creation. No unspecified reactions are permitted.

The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.

In the event of a conflict, the following parts of this section never take precedence over a rule that allows a poll to be created.

Each player may cast only one vote on a given poll; all votes cast by a player who voted for multiple options are ignored.

A poll closes when one or more of the following conditions is met:

* The poll is at least 24 hours old.
* All active players have voted on the poll, and there are more than two active players.
* A majority of active players have voted in favour of or against the poll, and there are more than two active players.

When a poll is closed, no more votes may be cast on it, and it may not be edited. If more players have voted in favour of the poll than against, the poll passes, otherwise, it fails.

#### <a name='rule-violation-polls'/> Rule violation polls

If a player ("the accusing player") believes that another player ("the accused player") has violated the rules, the accusing player may conduct a poll, called a "rule violation poll" or "RVP", to determine whether a forbidden action was performed. The poll must clearly state it is an RVP, and must specify the accused player, what sections/clauses of the rules they allegedly violated, and some proof of the violation.

In a rule violation poll, the following reactions are permitted:

* 👍: In favour of the poll, and in favour of a strike.
* 🤷: In favour of the poll, but against of a strike.
* 👎: Against the poll, and against a strike.

In a rule violation poll, any votes cast by the accused player or the author are ignored.

If the poll passes, the rule violation and its consequences must be reverted.

If the poll passes and more players are in favour of a strike (👍 reactions) than against (🤷 and 👎 reactions), the accused player may not perform any game actions for the next 24 hours.

### <a name='transactions'/> #transactions

The <#720025266256216176> channel may be used to modify quantities, but only in ways specifically allowed by other rules.

### <a name='factories'/> #factories

The <#720657721371918397> channel is used to announce actions related to factories.

Each player has a factory, which consists of zero or more buildings.

#### <a name='building-materials'/> Building materials

Building materials are quantities that can be spent in order to create buildings. Each subsection of this rule corresponds to a building material.

All building materials are tradable.

##### <a name='clay'/> Clay

Clay is a building material.

##### <a name='bricks'/> Bricks

Bricks are a building material. A player may spend 4 clay to create one bricks.

Players begin the game with 40 bricks.

#### <a name='buildings'/> Buildings

Each subsection of this rule corresponds to a building that can be built in a player's factory. If a subsection of this rule is deleted, any factories containing buildings of that type no longer contain those buildings.

The owner of a building is the player who owns the factory in which the building resides.

If a player has the necessary building materials (as detailed in the relevant subsection) to create a building, they may spend those materials to build that building in their factory. When a player builds a building, they must announce this in <#720657721371918397>, with a message of the form "Built (name of building)".

Buildings may have a power cost in fuel. If so, all operations using this building, unless otherwise specified, consume the specified amount of fuel to take place, and cannot take place if this requirement is not met. Buildings may also declare different power costs per operation.

A player may destroy any building that is not in use, removing it from their factory, by announcing "Destroyed (name of building)" in <#720657721371918397>.

In the above quotes, "(name of building)" should be replaced with the name of the relevant subsection.

For each subsection of this rule, there is an untradeable quantity with the same name (pluralized) as the subsection. Whenever a new subsection is created or a subsection is deleted, [**3. Quantities**](#quantities) must be updated to reflect this.

Whenever a player builds or destroys a building, that player's corresponding quantity must be updated to match the number of that type of building that that player has remaining.

##### <a name='mine'/> Mine

Required building materials: 40 bricks

If at least 8 hours have passed since they last did so, the owner of a mine may roll a 3-sided die, and carry out the effects as specified:

* 1: gain 40 clay
* 2: gain 100 fuel
* 3: gain 20 iron_ore

##### <a name='furnace'/> Furnace

Required building materials: 5 clay, 5 bricks

If at least have 30 minutes has passed since they last did so, the owner of a furnace may (at a power cost of 20 fuel/operation):

* change two of any quantity ending in "_ore" into one of the equivalent quantity that does not end with "_ore".
* change 2 clay into 1 bricks.

##### <a name='vet'/> Very Expensive Temple

The Very Expensive Temple cannot be built.

## <a name='quantities'/> Quantities

A quantity is a named property with a numerical value for each player.

By default any unique quantity added to the game:

* applies to all players.
* is instantiated at zero.
* must be an integer.
* must never have a negative value.
* cannot be traded.

The below list of quantities has no effect on the game. Any existing quantity that is not in the list may be added, along with an optional short description.

List of quantities:
* **fuel**
* **clay**: tradable, building material
* **bricks**: tradable, instantiated at 10, building material, made from clay
* **iron_ore**: found in mines
* **iron**: tradable, made from smelting iron_ore
* **dogecoin**: tradable, hard to mine.
* **mines**: untradeable. Tracks the number of Mines a player has built.
* **furnaces**: untradeable. Tracks the number of Furnaces a player has built.
* **very_expensive_temples**: untradeable. Tracks the number of Very Expensive Temples a player has built.

### <a name='trade'/> Trade

Any two players may exchange predetermined non-negative amounts of any two tradable quantities. Both players must make an announcement in <#720025266256216176>, clearly stating:

* who the other party is.
* which quantities will be traded.
* the amounts of each quantity that will be traded.

After a pair of matching announcements have been made, the players' quantities are changed according to the trade.

### <a name='dogecoin'/> Dogecoin

At any time, a player may give themselves any number of dogecoin.

## <a name='winning'/> Winning

When a player activates a Very Expensive Temple they own, that player wins.

When one or more players have won, the game ends.

## <a name='proposal-8'/> Proposal 8

Players cannot close Proposal #8.

## <a name='proposal-42'/> Résumé

Whenever the game ends, un-archive all Quonauts 9.5 game channels.

## <a name='rust'/> Rust

Rust is to be considered the best programming language. Ferris is to be considered its mascot.

