Version 2.0

Updated the repo to include the source code, per the license.

Changed tweaks:
- Remove Banned Mons From Lab: this was failing to exclude pseudo-legendaries. I have hard-coded it to exclude them, however I don't understand why the error was happening, and so it may not be fixed. If you use this and find a pseudo-legendary in the lab, please share the log with me, so I can debug it.

Version 1.6.1

Fixed an error with the Java Version. If you were able to use it before, it should still run now... but let me know if there are issues. This was kind of a weird error that came out of nowhere.

Version 1.6

Changed tweaks:
- Rebalance Encounters and Force Highest Level Encounters are now compatible.
- Revert Bad Berries now also bans these berries from showing up as wild held items or via Pickup.

Additionally, with the release of the official 4.6.0 randomizer: added support for randomizing Steven's team in the Mossdeep double in Emerald, and added support for held item randomization in DPPt and gen 6.

Version 1.5

Changed tweaks:
- Speed Up Friendship Evos: In Black/White, this sets base friendship to 207 instead of 215, to decrease the chance that the starter evolves before N.

Additionally, the randomizer now always outputs move data in the log. This allows the newest version of the NDS Tracker to work if your ROM has customized move names.

Version 1.4

Changed tweaks:
- Ban Unown From Wild: This is no longer available in FRLG, as FRLG already bans Unown from wild by default.

Additionally, the launchers have been included in the zip file.

Version 1.3

Changed tweaks:
- Increase Base Friendship: renamed to Speed Up Friendship Evos. Functionally unchanged, but in the future this may be changed to reduce the friendship required for pokemon to evolve, instead of increasing the base friendship. Requires the tracker to be updated first, though.
- Revert Resist Berries: changed to Revert Bad Berries. It now properly bans all berries that are banned by the 4.4 randomizer.
- Ban Imposter: changed to Lock Imposter to Ditto. It now prevents any pokemon besides Ditto from having Imposter, and guarantees that Ditto will always have Imposter.

Version 1.2

Changed tweaks:
- Rebalance Encounters: When Random Encounters are used (e.g. for Black/White Kaizo), this will move the highest-leveled encounters to the top of the encounter table, making them the most likely.

Version 1.1

Changed tweaks:
- Ban Unown From Wild works in FRLG too.

Added tweaks:
- 100% Non-Gym TMs: All TMs aside from those received from gyms will have full compatibility. Requires randomized TM compatibility of some kind. (Messes up Move Tutors, so don't use it if you care about those.)
- Rebalance Encounters: Wild encounters will still be available at the same levels, but the encounters and levels will be distributed to be more uniform. Requires Area 1-to-1 encounters, no additional rule, with Force Highest Level Encounters off.

The randomizer is now uploaded in a zip file, hopefully this should make people's antivirus less mad.

Version 1.0

This is built on version 4.6.0-dev of the [Pokémon Randomizer](https://github.com/Ajarmar/universal-Pokemon-randomizer-zx/releases). It includes some features which are not in the last official release.

Added tweaks:
- Force Highest Level Encounters: All wild pokemon will appear at only the highest level they can appear at. Requires Area 1-to-1 encounters, no additional rule.
- Increase Base Friendship: base friendship for all pokemon is increased to 215. (220 is required to evolve, so it will require a small amount of friendship grinding.) Requires random evolutions.
- Revert Resist Berries: type resistance berries such as Occa Berry are considered bad items, and no longer show up. Requires random field items.
- Remove Banned Mons From Lab: prevents legendaries and anything 600+ BST from being a starter.
- HM Moves by Levelup: HM moves are now available to be learned by levelup. (If you use this, make sure not to use them in the field if you don't have the HM item, or this can allow for sequence breaking.)
- Ban Unown From Wild: Unown cannot appear in the wild. Used in HGSS, where it can't appear until certain puzzles are solved and therefore wastes an encounter slot.
- Ban Perish Song: Perish Song can no longer be learned by levelup. (It can still be a TM.)
- Ban Imposter: Pokemon can no longer have the Imposter ability.
- Fix Mythical Pokemon Experience: Mew, Celebi, and Shaymin have 215 base experience, in line with other legendaries.
- Double % Increase: Trainer and wild pokemon % increase is doubled. (Intended for Emerald, which requires two randomizations due to the +60% rule.)

The randomizer currently works with all games from gens 3-6. If you want it for 1, 2, or 7, let me know (Something_Smart#8109 on Discord).

You are free to use this randomizer for any variant of Ironmon you want. But, keep in mind that many of these change the challenge, so you should put an asterisk with your run or otherwise indicate the rule changes.
