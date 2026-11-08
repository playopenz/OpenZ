# Building OpenZ from source

The [`source`](../source) folder of this repository holds the game code (C# and shaders) for reading. The complete
Unity project, with every model, texture, sound and scene, is attached to each release as source zips.

## Requirements

- **Unity 6.3 LTS** (6000.3.27f2 or a later 6000.3 patch) with the **Universal Render Pipeline** (URP 17.3). The
  packages in `Packages/manifest.json` are resolved automatically.
- Windows 10/11 with a DirectX 11/12 GPU. The game targets 60 fps. It was developed and tested on Windows only.
- EXPERIMENTAL, provided as they are: a Mac build (one app for Apple-chip and Intel Macs, ad-hoc signed only, never run
  on a real Mac), a Linux build (64-bit x86-64, never run on a real Linux machine) and touch screen and gamepad input
  (not tried on real devices).

## Open, play and build

1. Download **OpenZ_1.4_source_part1.zip** and **OpenZ_1.4_source_part2.zip** from the
   [latest release](https://github.com/playopenz/OpenZ/releases/latest) and unzip both into the same place (they merge
   into one `OpenZ_1.4_source` folder). In **Unity Hub** choose **Add → Add project from disk** and select that
   folder (the one that holds `Assets/`, `Packages/` and `ProjectSettings/`). The first open rebuilds `Library/` and
   takes a while.
2. Open `Assets/OpenZ/Scenes/MainMenu.unity` and press **Play**. All four levels are also playable directly:
   `L02_Desert.unity`, `L07_Volcanic.unity`, `L16_Jungle.unity` and `L17_CarPark.unity`.
3. To make a standalone game, open **File → Build Profiles**, choose **Windows** and click **Build**. The scene list is
   already set: Intro, MainMenu, L02_Desert, L07_Volcanic, L16_Jungle, L17_CarPark and UE_Playground (the Unit editor).
   **OpenZ → Menu → Set Build Order (MainMenu first)** puts the menu and the levels first again if needed. The
   experimental Mac and Linux builds have their own menus under **OpenZ**, **Mac experimental** and **Linux experimental**
   (they need the editor's Mac or Linux Build Support module, Mono).

Parity checks against the Zod Engine are under the **OpenZ** menu: *Run Parity Report*, *Run Bot Checks*,
*Run Pathing Stress Test* and *Audio → Write Sound Coverage Report*. The EditMode tests are in the Unity Test Runner.
Deliberate changes from Zod are listed by **OpenZ → Deviations → Write Deviations Block**: bridge auto-repair, a
higher driver-snipe chance, the level 2 head start and the Easy CPU.

[Back to the main page](../README.md)
