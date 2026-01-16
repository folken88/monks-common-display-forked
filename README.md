# Monk's Common Display (Fork)
Add-On Module for Foundry VTT

This module is used to display a common display for all players to view, such as a tv that your in person session can all view.
You do this by setting a player to be the common display and have them log into the account that is being displayed on that tv.
A handy control window allows you to specify how the screen is moved and what token to focus on.

## Installation
Simply use the install module screen within the FoundryVTT setup

## Usage & Current Features
You can set the common display player by either selecting the player in the settings window.

![monks-common-display](/screenshots/players.png)

Or by right clicking on the player in the players list and selecting `Set as Common Display`

![monks-common-display](/screenshots/player-list.png)

A player that is set to be common display will have a screen icon beside their name.

When you have a player selected as the common display, their ui will disappear, leaving just the viewing canvas. You can specify which parts of the screen you want to remain in the settings, in case you want to show the chat log, or the combat tracker.

When combat is active, the common display can show the active combatant's portrait next to the combat tracker. You can toggle the portrait, set its size (small/medium/large), and adjust opacity in the module settings.

Using the common display toolbar you can clear any journal entries or images that have been shared.
As well, as in the settings you can have shared images clear after a certain amount of time.
You can toggle the toolbar being on the screen by clicking on the icon on the regular toolbar.

![monks-common-display](/screenshots/toolbar.png)

You can also set what the screen on the common display will mirror or what token will be focussed, by right clicking the icon and selecting from the context menu.
And can toggle the feature on or off by clicking on the icon.

![monks-common-display](/screenshots/toolbar-menu.png)

## License
This Foundry VTT module, writen by Ironmonk, is licensed under [GNU GPLv3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), supplemented by [Commons Clause](https://commonsclause.com/).

This work is licensed under Foundry Virtual Tabletop <a href="https://foundryvtt.com/article/license/">EULA - Limited License Agreement for module development from May 29, 2020.</a>
