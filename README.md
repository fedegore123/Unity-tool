<img width="1254" height="1254" alt="Modular Hill Generator preview" src="https://github.com/user-attachments/assets/56df8403-fdc5-45ee-9ef7-4db85100d7da" />

# Modular Hill Generator for Unity

A Unity editor tool for building modular house layouts, previewing manual placements in the Scene view, and exporting the result as a prefab.

## What this tool does

- Generates modular layouts from wall, door, window, and floor prefabs.
- Supports profile-driven generation for repeatable setups.
- Lets you place walls and doors manually in the Scene view with hover feedback and snap preview.
- Can generate a top-surface collider and optional perimeter spikes.
- Exports the generated structure to a prefab for reuse in gameplay or level design.

## Why this repo exists

This is my first public Unity plugin and a practical tool I use for environment prototyping.
The goal is to keep it small, focused, and useful for game development workflows instead of turning it into a heavy framework.

## Installation

1. Download `ModularHill.unitypackage` from the repository root.
2. Open your Unity project.
3. Choose `Assets > Import Package > Custom Package`.
4. Select the package file and import everything required.

## Usage

1. Add the generator component to a GameObject in your scene.
2. Assign the prefabs used for walls, doors, windows, floor, and optional gameplay objects.
3. Adjust generation size, cell size, door placement, and collider options in the Inspector.
4. Use the Scene view tools to refine manual wall placement.
5. Export the generated result to a prefab when the layout is ready.

## Package layout

- `Assets/Plugins/ModularHill` — runtime assembly used by the generator.
- `Assets/_Project/Editor` — custom editor tooling and Scene view interactions.
- `Assets/_Project/Prefab` — modular building pieces.
- `Assets/_Project/Materials` — shared visual assets.
- `Assets/Scenes/SampleScene.unity` — example scene included with the package.

## Current status

This is an early public release and the tool is still evolving.
The current focus is to improve generation controls, add more modular parts, and tighten documentation and workflow.

## Roadmap

- Improve generation controls and layout rules.
- Add more modular building pieces and visual variations.
- Expand random seed and placement options.
- Improve documentation and sample scenes.
- Reduce setup friction for first-time users.

## Contributing

Issues and pull requests are welcome if they keep the tool focused and practical.
Please include Unity version, reproduction steps, and screenshots or a short video for editor changes.

## About

I am an independent game developer and technical artist building tools for Unity and game development workflows.
This project is part of a longer-term effort to build useful production tools and stronger open-source work.

## License

MIT License. See `LICENSE`.
