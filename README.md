# Puppy Powertools

This mod aims to just be a speedrunning mod with some minor Quality of Life features that are allowed for use in speedrun submissions.

This mod started as just a speedometer, but has evolved into a handful of independent modules that can be independently configured.

## Current Features

* Speedometer (lateral/vertical velocity components separated)
  * Optional precise position/facing direction info 
* Chapter timer for chapter runs
* on-the-fly powerprefs adjustment (currently just the Level Rush Shuffle seed)
* VFX toggling
  * You can turn off the sun! Lighting is unaffected; just the lensflare machine is gone.
  * Fireball's particle effects around the edge of the screen can be turned off.
* Card customization
  * You can dynamically replace the text that is drawn on cards
  * Color customization may or may not come at a later date, pending rule approval.

## Installation & Usage

This mod uses [MelonLoader](https://github.com/LavaGang/MelonLoader) as its modloader. Install that on your Neon White install first, and then run the game once so it generates some folders, and to verify it's installed (you should see a MelonLoader splash screen).

After that, grab the latest .dll from the [Releases page](https://github.com/PandorasFox/Neon-White-Mods/releases) and drop it in the "Mods" folder in your Neon White folder, e.g. `SteamLibrary\steamapps\common\Neon White\Mods`.

You will also need to install the **Mono Varient** of [Melon Preferences Manager](https://github.com/sinai-dev/MelonPreferencesManager/releases/) in order to configure this mod. Its default keybind is F5, but you can easily rebind it in-game.

The IL2CPP version of Melon Preferences Manager will **NOT** work. You **must** use the Mono variant.

### Additional Notes

You should probably add `--melonloader.hideconsole` to your game launch properties (right click the game in steam -> properties -> launch options at the bottom of that window) to hide the console that melonloader spawns. You really only need that if you're a mod developer; it's a weird default.
