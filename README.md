A [FoundryVTT](http://foundryvtt.com/) module that shows dice and bonus information when hovering over
an item/spell/ability/skills/etc. in an actor sheet.

<b>Only works with the SW5E system</b>

This is useful for those who:
* Want to roll physical dice, but still maintain all the convenience that Foundry provides.
* Want a quick lookup of what will be rolled for a particular attack, check, save, etc.

Tooltips are provided for the following areas of the character sheet:

|Hover Over|Displays|
|---|---|
|Ability|Ability Check<br/>Saving Throw|
|Item|Attack Roll<br/>Damage Roll<br/>Healing Roll<br/>Save DC|
|Short Rest|Remaining Hit Dice|
|Skill|Skill Check|

This has been tested with the following sheets:
* Default 5e Character Sheet
* Default 5e NPC Sheet
* Sky's Alternate 5e Sheet
* Tidy 5e NPC
* Tidy 5e Sheet

Your mileage may vary with other sheets.


Localization support is provided. Currently, only English is supported, but pull requests are welcome for
other languages.

# Installation

## Recommended

1. Go to Foundry's Setup screen
1. Go to the "Add-On Modules" tab
1. Press "Install Module"
1. Paste `Dice Tooltip3 - DnD5e` into the text field (this prob won't work)
1. Press "Install"

## Alternative

1. Download [this zip file](https://github.com/TheSirLancelot/dice-tooltip2/raw/master/dist/dice-tooltip2.zip)
2. Extract it into the `<FoundryVTT directory>/data/modules`-folder

# Compatibility

Only Firefox & Chrome are supported.

# Attribution & History

This module was originally written by Steffan Poulsen (https://github.com/SteffanPoulsen/dice-tooltip), and then again by Trevor Bechtel (https://github.com/trev33b/dice-tooltip2).

Trevor did great work, but it only worked with dnd5e. I needed it to work for sw5e, so here we are.
