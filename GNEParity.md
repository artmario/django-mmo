# GNE Parity #


## Locations ##

The model of hubs, each made up of lots exists.

At the moment there are two kinds of lots: accessible and inaccessible. There are no houses (not enough information online to implement them, I don't think)

Infrastructure for lot images exists but not many images have been created.

There are no shops yet. However, there is support for places where items are generated over time automatically.

It's not clear if you can drop things in shops in GNE.

There are no doors and so no other locations other than hubs and their lots. Sounds like GNE had one more location type: rooms.

## Players ##

Players exist but it is not possible to IM, make acquaintance (how do you make someone a friend?), make your enemy (not sure what that meant) or get info.

Players currently do not have a gender, real name or website, although they do have a level. There is no concept of houses.

Private messages are not possible.

## Items ##

Items exist and have a name and description, but not actions. The model supports them having an icon and weight. The small icon is used but not the weight. There is no info screen for them items so there is no get info. You can drop items but not any other item-type-specific actions. You cannot give items to other people currently.

Basic making support does exist.

## Home Page ##

This page does not yet exists.

So there is no link to who's online (or even concept of being online). There is no way to edit account details, discuss. There are no instructions, FAQs, high scores and no ability to make a suggestion, take a survey or logout (or even login).

The message on the GNE screenshot suggests a distinction between acquaintance and friend but I don't know the details.

## Interface ##

The actual layout is getting pretty close.

The hub name, description are done. Lots exist and may be accessed.

What's Here and Who's Here are displayed. It is possible to pick up items.

Chat is mostly done but Activity Log and Prefs are not done.

Notes and Contacts do not exist.

Making currently shows what can be made with the current inventory and lets you make those items. It is unclear what information was provided in GNE about making when the ingredients weren't in the inventory yet.

There is no map graphically shown.

Shekels, xp, and levels are shown but there is currently no way to get money or xp.

There is no concept of energy, mood or karma although these are displayed in their initial state.

There is a refresh but no report a bug or save & exit.

AJAX is used to independently update chat, who's here, and what's here.


## What's Here ##

This exists and works although there is no distinction between piles and unique items and no distinction between "pick up" and picking up 1 of a pile.

## Who's Here ##

This exists but there are no actions you can perform on other players from here yet.

## Who's Online ##

I think the only way to get to this in GNE is from the home page. I guess this was just a list.

It has not yet been implemented and there is not even a concept of a player being online.

## Chat ##

Chat models and UI now exists and game operations add to the chat window [r130](r130.md).

## Activity Log ##

No activity log models or UI yet.

Not clear what activities are shown with timestamps and which are not. Screenshot also shows reading, energy and xp. Reading and energy does not exists yet (although picking up and dropping items does, as done entering lots and hubs). xp is stored and displayed but nothing can yet change it.

## Preferences ##

Nothing existed here in GNE, so not much to implemented for parity :-)

## Inventory ##

This exists.

Piles of items are supported. Load is supported [r120](r120.md), as is dropping all [r131](r131.md). The only action available on an item in inventory is to drop a certain number in the pile. No distinction is made between unique items and piles.

## Notes ##

Notes do not yet exist.

It is not clear to me what 'archive' means nor what would come up under 'get info...' as opposed to 'read'. I also don't know whether public editable notes were partially editable or involve a wholesale replacement of the content.

## Making ##

Making is now implemented for normal items. There is no support for tool or people requirements.

It isn't clear what the interface looks like if you don't have the prerequisites. It's also not clear where the inprogress and done windows appear.

There is no concept of makingSkill yet, either.

Making is instantaneous whereas it took a while in GNE.

## Contacts ##

Does not yet exist. There is no concept of friends, acquaintances or enemies. There is no social index score.

## The Map ##

There is no graphical map yet.

## User Information ##

This is implemented although there is no way yet for balance or xp to change.

## User Statistics ##

Energy, mood and karma are in the model and are displayed but do not change.

There is nothing yet that removes or replenishes energy.

Mood and karma aren't particularly well explained in museum so I'm not sure how we'll implement those.

## Control Panel ##

There is refresh but no report a bug or save & exit.

## Launching The Game ##

Not much to say here :-)

## Badges ##

No badges yet :-)

## High Scores ##

This has not yet been implemented.

xp and cash exist (but not social index)

## Paper ##

Items exists and basic making (without tools) is implemented. It is now possible for items to spawn. There are no stores to sell paper in, though.

## Train Stations ##

There are no trains.

There is currently no support for door in lots.

## Social Network Explorer ##

Friendship relationships don't exist yet.