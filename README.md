# NES A4 and macro

My aim is to teach how to make application in XR Godot that you can load from two points in the space.

The aim is to learn Godot on the way and to finish an an exercice when you need to remove control your favority game from Xbox simulation tools for QA testing.

We will learn:
- How to read XR Input
- How to read Keyboard and Xbox Input in XR
- How to create interactive button with Godot XR Tools
- How to pick and move object in a XR scene and duplicate them
- How to create macro as text from 3D partition in space
- How to move and rotate an object by creating a drone and a steering car
- How to import assets from other application in Godot on Android
. - From Open Brush
  - From Open Blocks
  - From Gravity Sketch
  - From Downloads
- How to measure real world from Godot.
- How to create drone race track and load it on the real world.
- ...


```
git clone --recurse-submodules https://github.com/EloiStree/2026_02_22_godot_nes_a4_and_macro.git
```

```
# A tool that turns 3D object positions from two-point distances into macro text to execute by an interpreter
git submodule add https://github.com/EloiStree/2026_02_22_gdp_3d_macro_partition.git addons/2026_02_22_gdp_3d_macro_partition

# A tool to load a scene from two-point distances on a flat horizontal or vertical surface
git submodule add https://github.com/EloiStree/2025_06_05_gdp_two_points_quad_loader.git addons/2025_06_05_gdp_two_points_quad_loader

# Toolbox to simulate keyboard and Xbox input from an NES format, with a basic macro interpreter and input reading tool
git submodule add https://github.com/EloiStree/2026_01_18_gdp_nes_controller_udp.git addons/2026_01_18_gdp_nes_controller_udp


# Allows importing files from the Quest into Godot, similar to Open Brush Blocks or Gravity Sketch
git submodule add https://github.com/EloiStree/2025_09_15_gdp_import_assets_on_quest.git addons/2025_09_15_gdp_import_assets_on_quest

# A small vehicle like a toy from Amazon that you can steer with four buttons to make a small game
git submodule add https://github.com/EloiStree/2025_10_19_gdp_kid_toy_skid_steering.git addons/2025_10_19_gdp_kid_toy_skid_steering

# A small flying drone without physics that can move around to make small games and learn
git submodule add https://github.com/EloiStree/2025_04_15_gdp_kid_toy_ovni_code.git addons/2025_04_15_gdp_kid_toy_ovni_code

# A tool to access the webcam of the device (here the Quest 3)
git submodule add https://github.com/EloiStree/2025_11_14_gdp_webcam_to_texture.git addons/2025_11_14_gdp_webcam_to_texture

# A JDG fun Patoune 3D model with a script that requires you to catch all objects to complete the quest
git submodule add https://github.com/EloiStree/2024_10_02_gdp_patoune_race.git addons/2024_10_02_gdp_patoune_race

# Some track race for building drone game.
git submodule add https://github.com/EloiStree/2024_06_31_gdp_drone_race_checkpoint.git addons/2024_06_31_gdp_drone_race_checkpoint





```


To Add:

