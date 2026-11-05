<img src="docs/icon.svg" width="96" height="96" align="right" alt="Godot Analyze icon">

# Godot Analyze
**This is the public issue tracker of the Godot Analyze plugin for JetBrains IDEs.**

Godot Analyze is **a type-aware GDScript and Godot 4 toolkit for IntelliJ IDEA and Rider** – compiler-grade inspections, scene-aware navigation, refactorings, formatter, run configurations and debugger.

<br>[website](https://fvoidhe.github.io/godot-analyze-plugin/) · [bug tracker](https://github.com/fvoidhe/godot-analyze-plugin/issues) · [report a bug](https://github.com/fvoidhe/godot-analyze-plugin/issues/new?template=bug_report.yml) · [request a feature](https://github.com/fvoidhe/godot-analyze-plugin/issues/new?template=feature_request.yml)
<br>
<br>

- **Type-Aware Code Insight**: Types are inferred across scripts, scenes and the engine API. Completion, Go To Declaration and Find Usages follow `class_name`, `extends`, `preload()`, `get_node()` / `$Node` paths and exported properties.
- **Compiler-Grade Inspections**: 25+ inspections modeled on the Godot compiler – incompatible assignment, return and argument types, wrong argument counts, unresolved members, override signature mismatches, assignments to constants, unreachable code, shadowed identifiers, invalid annotations, and more.
- **Smart Completion**: Engine and project classes, members, signals, enums and `res://` paths. Picking `filter`, `map`, `any`, `all`, `sort_custom` or `reduce` expands a ready-to-fill lambda.
- **Inlay Hints**: Inferred node types of `get_node()`, resolved resource types of `preload()`, parameter names at call sites, and declared types of exported properties right inside `.tscn` / `.tres` files.
- **Rename Refactoring**: Rename functions, global classes and scene nodes without breaking references in scripts and scenes.
- **Scene and Resource Files**: `.tscn`, `.tres`, `.import` and `project.godot` are fully parsed – highlighting, navigation for `ExtResource`, `SubResource`, node paths and `uid://` references.
- **Signal Connections**: Gutter markers link `[connection]` entries in scenes with the script methods they call, in both directions.
- **Override Markers**: Gutter icons for overriding and overridden functions, and for nodes overridden in inherited scenes.
- **Scene Tree Tool Window**: Browse the node tree of the current scene with Godot's own node icons, attached scripts, unique names, visibility and connected signals.
- **Engine Documentation**: Quick Documentation and parameter info come from the class reference of your Godot version, in both IntelliJ IDEA and Rider.
- **Formatter**: Godot-style indentation for blocks, brackets and continuation lines, plus blank-line rules between declarations.
- **Run Configurations**: Run the project or the current scene with any registered Godot installation; resources are imported before launch.
- **Debugger**: Set breakpoints in GDScript and debug with the IDE debugger – stepping, call stacks and variables, for Godot 4.0 and newer.
- **Godot Editor Integration**: Open or bring forward the Godot editor and switch the project's Godot version from the main toolbar. Manage multiple installations in *Settings → Languages & Frameworks → Godot Installations*.
- **Helpers**: Code folding, commenting, spell checking, smart Enter in strings, copy `res://` path, and more.

<br>
<br>

Requires a JetBrains IDE **2026.2** or newer and **Godot 4.x**. Install it from *Settings → Plugins → Marketplace* by searching for **Godot Analyze**.

<br>The Godot logo is by Andrea Calabró, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Godot editor icons are © Godot Engine contributors, MIT license. This plugin is not affiliated with or endorsed by the Godot Foundation.
