
# First-time setup

To obtain the best experience, there are a few things you should do after installing Project OutFox. Some of these instructions assume usage of the included default theme (Soundwaves).

## Selecting a game type

When launching Project OutFox for the first time and without save data present, you will be prompted to select which **game type** you would like to begin with. Project OutFox supports a variety of game types, which simulate different types of rhythm games (including button layouts and, where applicable, gameplay behaviours specific to the game type). Game types are further divided into **styles**, which include chart types such as single, double, etc.

![Screenshot of the Project OutFox game selection screen.](./_media/getting-started/select-game-type.png)

As of Alpha 4.9.7, they include:

* **dance** - the default game type. Similar to games such as _Dance Dance Revolution_ and _In the Groove_, it uses four lanes designated by cardinal directions (left, down, up, right).
* **pump** - A five-lane dance game, which uses four diagional directions and the center rather than cardinal directions.
* **kb7** - A seven-lane game type similar to games such as _O2Jam_, with six keys flanking a centre column (usually mapped by default to the SDF, JKL, and space keys by default)
* **ez2** - A game type based on the defunct arcade game _EZ2Dancer_, which uses three foot panels and a pair of hand sensors.
* **para** - A dance game designed for _para para_ routines, which is typically played with five infrared hand sensors in a semicircular layout, and uses a considerably looser scoring system.
* **ds3ddx** - A dance game whose format is common among Chinese arcade dance games, which uses four diagional foot panels, and four hand sensors around the pad in the cardinal directions.
* **beat** - A BMS player mode, supporting 5-key and 7-key styles, and the ability to load BMS files.
* **maniax** - A game type based on the defunct arcade game _Dance Maniax_, which uses four hand sensors arranged into two columns (upper and lower).
* **techno** - Similar to ``dance``, except supporting up to eight panels (cardinal and diagional directions)
* **popn** - A PMS player mode, supporting 5-button and 9-button styles, and the ability to load PMS files.
* **gddm** - A drum mode supporting five-drum (with one bass pedal) and seven-drums (two pedals) styles, modelled upon the mechanics of the arcade rhythm game _DrumMania_.
* **guitar** - A guitar mode supporting three-button and five-button game types, modelled upon the mechanics of the arcade rhythm game _Guitar Freaks_.
* **kickbox** - A mode that was originally designed for an exercise setup.

?> **Tip** You can switch between game types at any time using the "Select Game" button on the main menu.

## Configuring your controls

Each game type has its own default keyboard configuration; dance, for example, maps the first player to the arrow keys (when playing on keyboard, this is often referred to as the "index" playstyle). To configure your button mappings, go to **Options > Input & Calibration > Config Key/Joy Mappings**. 

![Navigating to the Config Key/Joy Mappings screen.](./_media/getting-started/gotoconfigjoy.jpg)

Use the arrow keys to select an item to map, press Enter, and then press the button on the keyboard or controller you want to use. You can have multiple button assignments for each command.

![The Config Key/Joy Mappings screen.](./_media/getting-started/config-joy.png)

Project OutFox supports a wide variety of controllers and even arcade hardware. By default, the game operates with a HIDAPI and XInput-compliant input engine. If your controller does not perform as well or function as expected, you can switch to the alternate XInput input mode from the **Experimental Options** menu. XInput will sometimes also require you to map your controller to the input engine's virtual gamepad, allowing the game to properly interface with the device. The **Map Controller** screen is available from the **Input & Calibration** menu.

![The Exerimental Options screen. Input mode selector is highlighted.](./_media/getting-started/enable-hidapi.jpg)

## Calibrate your audio sync

In a rhythm game, timing is everything. But latency produced by your audio outputs can affect your accuracy. You can interactively adjust the audio **offset** using the **Calibrate Audio Sync** option in the **Input & Calibration** menu.

![Navigating to the Calibration screen.](./_media/getting-started/calibrate-sync.jpg)

A song will play with a pattern of alternating notes; in the dance game type, they will be left and right arrows. Tap them to the rhythm **based on what you hear**. Every 24 notes, your inputs will be used to calculate a new offset; watch for "Perfect" and "Flawless" judgements.

![Audio calibration screen.](./_media/getting-started/sync-screen.jpg)

The song will continue playing on a loop until you exit with the ``Back`` button (mapped to Escape by default), after which you will be given an opportunity to save the changes. If you wish to calibrate in-game with your song of choice, you can press ``F6`` twice during gameplay to enable **AutoSync Machine**, which will last until the end of the song or when exited with the ``Back`` button. A message will appear asking to confirm your changes and if you wish to apply them or not.

## Create a profile

While Project OutFox can save some data to a global "machine profile", it is recommended that you create a local profile so you can save personal high scores, as well as player settings (such as modifiers) that can persist between sessions.

You coan manage profiles from **Options > Profiles**. From here you can create a profile, and edit existing profiles.

![Navigating to the Profiles screen and selecting to create a profile.](./_media/getting-started/create-profile.jpg)

From the profile editor (highlight a profile and press Start, and then select "Edit profile"), you can input fitness-related information, change the layout of the optional "Detailed Stats" pane during gameplay, and add an avatar to your profile (avatars are loaded from the Appearance/Avatars directory).

![Editing a profile.](./_media/getting-started/profile-screen.jpg)
