# Godot 3 .gitignore

This is a sample `.gitignore` file for Godot 3 projects. It includes common exclusions for Windows, macOS, and Linux.

I have custom folders within my Godot projects which are also excluded here which are:

- `.resources` - This is where I put all things that shouldn't come with the Godot project export such as \*.psd files.
- `.bin` - This is where I dump the project exports where they'll have their respective folders: `win32`, `macOS`, `linux`, `web`, `android`, `ios`, `uwp`.