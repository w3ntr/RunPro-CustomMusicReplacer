# Custom Music Replacer for Run Pro

A Lightweight utility mod for **Run Pro** that enables dynamic background music replacement with custom audio tracks.

## Overview

Custom Music Replacer allows players to swap standard in-game soundtracks with local `.wav` audio files. The mod features real-time memory audio overriding, an interactive graphical user interface (GUI), and keybinding configuration.

## Features

* **Zero-Delay Audio Replacement:** Replaces default track references instantly upon initialization.
* **Interactive In-Game GUI:** Press `F7` to open the control panel.
* **Force Playback:** Trigger specific custom songs manually via the menu.
* **Live Volume Adjustment:** Fine-tune music volume without re-instantiating audio memory clips.
* **Custom Keybindings:** Rebind the menu activation key directly within the interface.
* **Persistent Settings:** Automatically exports and loads user configuration via `MelonPreferences`.

## Requirements

* **Game:** Run Pro
* **Mod Loader:** [MelonLoader](https://github.com/LavaGang/MelonLoader) (v0.6.0 or higher)

## Installation

1. Download the latest `CustomMusicReplacer.dll` from the Releases section.
2. Place `CustomMusicReplacer.dll` inside the `Mods` directory of your Run Pro installation folder.
3. Launch the game once to automatically generate the `UserData/CustomMusic` folder.
4. Place your custom `.wav` files into `UserData/CustomMusic`.

> **Note:** Audio files must be formatted as 8-bit, 16-bit, or 32-bit PCM `.wav`. Match the file name with the original game track name (refer to `music_tracks_list.txt` generated in the same directory).

## Controls & Usage

* **Toggle Menu:** `F7` (Default)
* **Rescan Folder:** Re-indexes local audio files without restarting the game.
* **Menu Key Rebind:** Click the keybind button in the menu and press any key to update the shortcut.

## License

Distributed under the MIT License. Feel free to modify and contribute.
