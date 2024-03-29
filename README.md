[![Current Release](https://img.shields.io/github/v/release/sneakyevil/SD-RenderTweaker?label=Current%20Release&color=red&id=0)](https://github.com/sneakyevil/SD-RenderTweaker/releases/latest/download/Release.zip)
![Downloads](https://img.shields.io/github/downloads/sneakyevil/SD-RenderTweaker/total?label=Total%20Downloads&color=red&id=0)
![Latest Downloads](https://img.shields.io/github/downloads/sneakyevil/SD-RenderTweaker/latest/total?color=red&label=Latest%20Downloads&id=0)

<details>
  <summary>Feature List</summary>
  
  - Camera:
    - FOV
    - Vehicle:
        - Disable Auto Center
        - Auto Center Timer
        - Center Speed
        - Disable Noise
        - Disable Reverse
  - Game:
    - Highlight:
      - Attacking Character (Combat)
      - Environment Objects (Combat/Grapple)
    - World Effects:
        - Disable Health UI
  - Renderer:
    - Ambient Occlusion (AO)
    - Anti Alias (AA)
    - Depth Of Field (DOF)
    - Hair Blur
    - HDR Bloom
    - Planar Reflections
    - Sky Irradiance Volumes
  - Shadows:
    - Allow Spots
    - Split (0, 1, 2)
    - Bias
  - Hud:
    - Health Meter
    - Minimap
    - Face Meter
    - Weapon Ammo
    - Popup:
      - Mission Scoring (Police/Triad XP)
      - Region Indicator
      - Social Award
      - Objective Indicator
    - Overlay:
      - Action Buttons (Combat, Arrest, etc...)
      - Action Prompts (Vault, Sleep, etc...)
      - Crosshair
      - Objective Indicator
  - UI:
    - Text:
      - Global Scale Factor
    - Subtitles:
      - Enable
      - Scale Factor
</details>
<details>
  <summary>Game Bug Fixes</summary>
  
  - Game window overlap to 2nd monitor in fullscreen mode.
</details>

---

# Installation
1. First check readme from SDmodding org: [Here](https://github.com/SDmodding/.github/blob/main/profile/README.md)
2. Download latest [Release.zip](https://github.com/sneakyevil/SD-RenderTweaker/releases/latest) file from Release or by [Clicking here](https://github.com/sneakyevil/SD-RenderTweaker/releases/latest/download/Release.zip).
3. Extract all files inside game folder
5. Launch game
6. If everything was installed properly you should be able to open the UI by pressing `F10`.
<details>
  <summary>Note for Linux Users:</summary>
  
  - You need to use launch option for game: `WINEDLLOVERRIDES="dinput8=n,b" %command%` this will make sure the dinput8.dll is used from game directory instead native dll provided by wine/proton.
  - This is needed because dinput8.dll is asi loader that allows it to load this modification!
</details>

# Preview
![Preview](https://github.com/sneakyevil/SD-RenderTweaker/assets/29150970/10f9af4e-beb9-4874-8d1e-0518a2b778c3)

# Bug Reports/Requests
If there is any bug or you got any request, open the issue and properly describe about the thing.
