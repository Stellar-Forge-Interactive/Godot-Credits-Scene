# Notice
This is a repack of [Maaack's Credits Scene](https://github.com/Maaack/Godot-Credits-Scene) intended to be used as a submodule. This is not our original work.

# Godot Credits Scene
For Godot 4.5 (4.3+ compatible)

This credits scene scrolls text that is read from an attribution file in a markdown (`.md`) format.

[Example on itch.io](https://maaack.itch.io/godot-game-template)  
_Example is of [Maaack's Game Template](https://github.com/Maaack/Godot-Game-Template), which includes additional features._

## Objective

For adding scrolling credits to your scenes that can auto-update from a project's `ATTRIBUTION.md`, `CONTRIBUTORS.md`, or similar attribution markdown file.

## Features

- Classic scrolling text.
- Interactable:
  - Supports mouse-wheel and touch-pad scrolling.
  - Supports clicking on external links.
- Generates content from reading an attribution file in markdown (`.md`) format.
- End Credits example scene.
- Assisted plugin installation.

### How it Works

- `Credits.tscn` reads from `ATTRIBUTION.md` to automatically generate the content for it's scrolling text label.  

## Installation

### GitHub (Submodule)

*this assumes you aren't using an IDE that can do this for you.*

1. From your project root, open a terminal in your project's `addons/` directory, creating it if it doesn't exist.
2. run `$ git submodule add https://github.com/Stellar-Forge-Interactive/Godot-Credits-Scene.git`

### GitHub (Manual)


1.  Download the latest release version from [GitHub](https://github.com/Maaack/Godot-Credits-Scene/releases/latest).  
2.  Extract the contents of the archive.
3.  Move the `addons/maaacks_credits_scene` folder into your project's `addons/` folder.  
4.  Open/Reload the project.  
5.  Enable the plugin from the Project Settings > Plugins tab.  
    If it's enabled for the first time,
    1.  A dialogue window will appear asking to copy the example scenes out of `addons/`.
6.  Continue with the [Existing Project Instructions](/addons/maaacks_credits_scene/docs/ExistingProject.md) 

### Godot Asset Library
This package is available as a plugin, meaning it can be added to an existing project. 

![Package Icon](/addons/maaacks_credits_scene/media/credits_scene-icon-black-transparent-256x256.png)  

When editing an existing project:

1.  Go to the `AssetLib` tab.
2.  Search for "Maaack's Credits Scene".
3.  Click on the result to open the plugin details.
4.  Click to Download.
5.  Check that contents are getting installed to `addons/` and there are no conflicts.
6.  Click to Install.
7.  Reload the project (you may see errors before you do this).
8.  Enable the plugin from the Project Settings > Plugins tab.  
    If it's enabled for the first time,
    1.  A dialogue window will appear asking to copy the example scenes out of `addons/`.
9.  Continue with the [Existing Project Instructions](/addons/maaacks_credits_scene/docs/ExistingProject.md)  


### Extras or Components

Users that want additional features can try [Maaack's Game Template](https://github.com/Maaack/Godot-Game-Template) or other options from the [plugin suite](/addons/maaacks_credits_scene/docs/PluginSuite.md).  

## Usage

### Existing Project

[Existing Project Instructions](/addons/maaacks_credits_scene/docs/ExistingProject.md)  

### More Documentation

[Automatic Updating](/addons/maaacks_credits_scene/docs/AutomaticUpdating.md)  

---

## Community

Join the [Discord server](https://discord.gg/AyZrJh5AMp ) and share your work with others. It's also a space for getting or giving feedback, and asking for help. 
 

## Links
[Attribution](/addons/maaacks_credits_scene/ATTRIBUTION.md)  
[License](/addons/maaacks_credits_scene/LICENSE.txt)  
[Godot Asset Library](https://godotengine.org/asset-library/asset/2932)  
