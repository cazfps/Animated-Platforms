# Animated Platforms

An animated ground plane for Blockbench to preview motion (walk cycles, vehicles, etc.) by scrolling a textured plane under your model.

This is especially useful for Minecraft mobs / entity animation, but it works for any animation workflow.

![ogre_platform_demo](https://github.com/user-attachments/assets/108121ed-9c42-4cda-b6a7-bdcb51d64c42)

## Features
- Scroll speed in blocks/sec (with quick presets)
- Size/placement controls (width/length/height, rotation)
- Optional custom texture + rotate/flip
- Texture library for quick reuse
- Per-animation presets (save / auto-save)

## Notes
- Custom texture rotation is visual only; movement direction stays consistent.
- Presets are stored locally (Blockbench localStorage) and are scoped so different projects/animations don’t overwrite each other.

## How to import it to your blockbench

Go to File -> Plugins -> Load Plugin from File 

Then Paste this 
```https://raw.githubusercontent.com/cazfps/Animated-Platforms/refs/heads/main/animated_platforms.js```


<img width="671" height="561" alt="image" src="https://github.com/user-attachments/assets/5631c64f-1a3a-4b0a-8f09-9a7e5b5d972f" />

  
## Author
Cazfps
