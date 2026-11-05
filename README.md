<p align="center">
  <img src="docs/icon.svg" width="96" height="96" alt="Godot Analyze icon">
</p>

<h1 align="center">Godot Analyze</h1>

<p align="center">
  GDScript and Godot scene support for JetBrains IDEs.<br>
  <a href="https://fvoidhe.github.io/godot-analyze-plugin/">Website</a> ·
  <a href="https://github.com/fvoidhe/godot-analyze-plugin/issues/new/choose">Report an issue</a>
</p>

---

This repository is the public home of the **Godot Analyze** plugin: documentation, release notes and the issue tracker.
The plugin source code is not published here.

## Features

### GDScript
- Syntax and semantic highlighting, code folding, commenting, spell checking
- Code completion for engine classes, project classes, members, signals, enums and resource paths
- Go to declaration, find usages, rename (functions, global classes, scene nodes)
- Type inference with inlay hints for `get_node()`, `preload()` and call arguments
- Parameter info and quick documentation backed by the engine API
- Override / overridden gutter markers for functions
- Code formatter with Godot-style indentation and blank-line rules
- 25+ inspections mirroring the Godot compiler: type mismatches in assignments, returns and call
  arguments, unresolved members, unreachable code, shadowing, invalid annotations, override
  signature mismatches, and more

### Scenes and resources (`.tscn`, `.tres`, `.import`, `project.godot`)
- Highlighting and navigation for `ExtResource` / `SubResource` / node path references
- Exported script property types shown next to their values in scenes
- Signal connection markers linking scenes and script methods
- Scene tree tool window with node icons, script attachment and connected signals
- Copy a file's `res://` path

### Run and debug
- Godot run configurations, including running a scene directly from the editor
- Breakpoints and debugging of GDScript through the IDE
- Open or focus the Godot editor and switch the Godot version from the toolbar
- Manage multiple Godot installations in *Settings → Languages & Frameworks → Godot Installations*

## Requirements

- A JetBrains IDE, version **2026.2** or newer
- Godot **4.x**

## Installation

In your IDE, open *Settings → Plugins → Marketplace*, search for **Godot Analyze** and click *Install*.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/fvoidhe/godot-analyze-plugin/issues/new/choose).
For bugs, please include your IDE version, plugin version and Godot version, and a minimal GDScript or scene snippet if possible.

## Credits

The Godot logo is by Andrea Calabró, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Godot editor icons are © Godot Engine contributors, MIT license.
This plugin is not affiliated with or endorsed by the Godot Foundation.
