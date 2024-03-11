![Logo](https://github.com/YunyunsFriends/Konosuba-Verdia-EN-Full/blob/c15937e56e6404d2c7b5bf7da0acba5da8374be7/githubassets/Logo.png)
# KonoSuba: Verdia of the Resurrection 100% English Patch

### Launcher Change Log:

- Replaced Japanese text with English translations.
- Added a default controls option in the Keyboard/Gamepad config.
	- This option was added due to it not being possible to configure the gamepad controls on the Steam Deck.
- Removed the ability to resize the launcher window.
- Removed leftover Steamworks integration for Pharaoh Rebirth.
- Due to issues with virus scanners flagging the newly compiled executables as malicious, the launcher has been compiled to load an external data file and modules to combat this issue.
- Rebased on Clickteam Fusion 2.5+ Build R294.14 (Originally based on Build 287).

### Game Change Log:

- Replaced all Japanese text (Names, Quests, Lists, Textures, Ect.) with English translations.
- Rebased on Clickteam Fusion 2.5+ Build R294.14 (Originally based on Build 287).
- Set the game to be displayed with a forced aspect ratio of 16:9.
	- This fixes the game stretching to fill the screen on non-16:9 aspect ratio displays like the Steam Deck or ultrawide monitors.
- Fixed various bugs found in the original release.
	- Fixed: Aqua's magic attacks freezing when Aqua is frozen as it was inconsistent with other bosses.
	- Fixed: A certain boss's flames not disappearing when frozen.
	- Fixed: On the weapon receiving screen and the credits "S" would have garbled pixels appearing next to it.
- Updated the name/dialogue font to ABeeZee. Replacing nukamiso_2004_beta08 as the default font.
- Added an apostrophe and an underscore to the pixel art font.
- Removed the tutorial signs from Aqua, Megumin, and Darkness's stages and moved them to the Opening Stage.
- Slight tweaks were made to the first and final cutscenes.
	- The opening cutscene was changed to have three sprites change off screen instead of just before.
	- Timing changes were made to the opening cutscene for a newly added line.
	- The final cutscene has a character's sprite change one line earlier.
- Slightly adjusted the level design of the Opening Stage to tech the player how to use the dash jump.
- Updated Notzan ACT tracks with higher quality versions from AudioStock on the stages listed below.
	- Aqua's stage - Submarine.
	- Stage 5 - Confrontation.
	- Stage 6 - Closed Room, Escape, Confrontation, Behind the Truth.
- Stage 6's boss fight has a new track added.
- Added Discord Rich Presence.
- Due to issues with virus scanners flagging the newly compiled executables as malicious, the game has been compiled to load an external data file and modules to combat this issue.
- Changed the window header to "KonoSuba: Verdia of the Resurrection".

Decompiled/converted with CTFAK 2.2: The Definitive Update

### Known Issues:

- There is a possibility to damage the Giant Toads with Create Water. (Original Release Bug)
- Skill text may disappear when pressing Attack to consume an HP or MP restoring item while in the selection menu. (Original Release Bug)
- "Nature's Wonders" may do slightly more damage than the original release.
- In the launcher, the "Use D-pad Input" option does not function properly on the Steam Deck, use controller remapping or keyboard input to use the d-pad.
- On the Steam Deck, the font used for the parts of the copyright text and level difficulty text is not available/does not function properly under W.I.N.E./Proton and will not display certain Unicode characters.
- Utilizing other translations' dial.dat files will result in a few timing issues with cutscenes, while not game-breaking this mod was made with our own translation in mind.

### Credits:

Deux_Mechina
- Project Leader
- Translator

Shaggy_Thecat
- Bug Fixing
	
Striker
- Proofreading

### Special Thanks:

CTFAK
	- This program allowed us to convert or "decompile" the game back to a .MFA file to load into Fusion.
	- https://github.com/CTFAK

AudioStock
	- Has a variety of stock audio form Japanese composers such as Notzan ACT, which has various tracks licensed for the game.
	- https://audiostock.net/

Google Fonts
	- A resource of open source fonts. ABeeZee-Regular was used in this mod.
	- Licensed under the Open Font License. Can be found in the "font" folder.
	- https://fonts.google.com/
	- https://openfontlicense.org/

Team Ladybug
        - For developing such a wonderfully high quality game!

Kurone Mishima and The KONOSUBA Animation Staff
        - For all their passionate work for this wonderful series!
