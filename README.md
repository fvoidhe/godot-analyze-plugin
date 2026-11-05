<p align="center">
  <img src="docs/icon.svg" width="96" height="96" alt="Godot Analyze icon">
</p>

<h1 align="center">Godot Analyze</h1>

<p align="center">
  <b>This is the public issue tracker of the Godot Analyze plugin for JetBrains IDEs.</b>
</p>

<p align="center">
  Godot Analyze is <b>a native GDScript and Godot 4 IDE for every JetBrains IDE</b> – plug and play, no language server, no Godot editor in the background. Open as many projects as you like and get deep analysis, precise navigation and rename, rich engine docs and scene tooling out of the box.
</p>

<p align="center">
  <a href="https://fvoidhe.github.io/godot-analyze-plugin/">website</a> ·
  <a href="https://github.com/fvoidhe/godot-analyze-plugin/issues">bug tracker</a> ·
  <a href="https://github.com/fvoidhe/godot-analyze-plugin/issues/new?template=bug_report.yml">report a bug</a> ·
  <a href="https://github.com/fvoidhe/godot-analyze-plugin/issues/new?template=feature_request.yml">request a feature</a>
</p>
<br>

## Why Godot Analyze

- **Plug and Play**<br><sub>Install, open a folder with <code>project.godot</code>, done. The engine API for your Godot version ships with the plugin – completion, docs and checks work without launching Godot.</sub>
- **No Language Server**<br><sub>Analysis runs on the IDE's own indexes, with no editor process or LSP port per project. Open any number of Godot projects side by side, each with the full experience.</sub>
- **Deeper Analysis**<br><sub>Scripts and scenes are analyzed together. In <code>@onready var sprite = $Body/Sprite</code>, the type comes from the node in the <code>.tscn</code>, so completion and inspections treat <code>sprite</code> as a <code>Sprite2D</code>.</sub>
- **Rich Documentation**<br><sub>Quick Documentation on any engine class, method or property shows the official class reference for your Godot version, with clickable links to related classes and members.</sub>
- **Scene Management**<br><sub>A Scene Tree tool window shows the open scene with Godot's icons and each node's signals. Gutter icons link every <code>[connection]</code> in a scene to its handler method and back.</sub>

## Features

- **Type-Aware Code Insight**<br><sub>Types inferred across scripts, scenes and the engine API.</sub>
- **Compiler-Grade Inspections**<br><sub>25+ checks modeled on the Godot compiler, such as argument types, return values, unreachable code and <code>$</code> used outside a Node.</sub>
- **Smart Completion**<br><sub>Classes, members, signals, enums and <code>res://</code> paths.</sub>
- **Inlay Hints**<br><sub>Node, resource and parameter types shown inline – <code>$Body/Sprite</code> displays <code>Sprite2D</code>.</sub>
- **Rename Refactoring**<br><sub>Renaming a scene node updates <code>$</code> paths in scripts, <code>NodePath</code> values and connections in scenes, and the same node in inherited scenes. Renaming a function also updates the <code>method</code> of its <code>[connection]</code>.</sub>
- **Scene and Resource Files**<br><sub>Full support for <code>.tscn</code>, <code>.tres</code>, <code>.import</code> and <code>project.godot</code>.</sub>
- **Signal Connections**<br><sub>Jump from a <code>[connection]</code> in a <code>.tscn</code> to its handler method, and from the method back to every connection.</sub>
- **Override Markers**<br><sub>Gutter icons for overridden functions and inherited nodes.</sub>
- **Scene Tree Tool Window**<br><sub>The current scene's node tree, with Godot's own icons.</sub>
- **Engine Documentation**<br><sub>Class reference for your Godot version, right in the editor.</sub>
- **Formatter**<br><sub>Godot-style indentation and blank lines.</sub>
- **Run Configurations**<br><sub>Run the project or the current scene.</sub>
- **Debugger**<br><sub>Breakpoints, step into/over/out, run to cursor and variable inspection in the IDE debugger.</sub>
- **Godot Editor Integration**<br><sub>Open the editor and switch Godot versions from the toolbar.</sub>
- **Helpers**<br><sub>Folding, commenting, spell checking and more.</sub>

<br>

## Install

1. Open *Settings → Plugins → Marketplace* in your IDE.
2. Search for **Godot Analyze** and click *Install*.
3. Open a folder that contains `project.godot`.

Works in any JetBrains IDE **2026.2** or newer, including the free and open-source editions. Requires **Godot 4.x**.

> [!IMPORTANT]
> **Rider users:** Rider bundles the *Godot Support* plugin, which registers the same languages and file types. Disable it in *Settings → Plugins → Installed* and restart the IDE before using Godot Analyze. Other IDEs need no extra steps.

<br><sub>The Godot logo is by Andrea Calabró, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Godot editor icons are © Godot Engine contributors, MIT license. This plugin is not affiliated with or endorsed by the Godot Foundation.</sub>
