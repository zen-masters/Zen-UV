## Version 2.2.1

### General

- Added **Texel Density Presets** system.
- Added **Arrange** operator to **Distribute** tool for grid distribution of islands.
- Improved functionality for the add-on updating. (Use new **Update** button ****instead of **Install** to avoid errors when updating)

### Operators

#### **Unwrap**

- Updated **Zen Unwrap** operator. **Switch Seams** option is disabled in the default state.
- Updated  **Zen Unwrap** Undo functionality.
- Fixed a bug with **Selected Only** option of **Zen Unwrap** operator. Now it does not affect neighboring polygons.

#### **Pack**

- Added **Packing Mode** settings (Single Tile, Tiles, Groups Together, Groups to Tiles) ****for UVP2 Pack Engine.
- Updated **Pack System** settings, they have been moved to a separate panel.
- Fixed a bug when the UVP2 version does not have some functions. Added a message about the need to update.

#### **Checker Map**

- Added **Interpolation** option to disable smoothing of the checker texture.
- Fixed a bug with **Display Stretch Map** operator if the island is critically small.

#### **Stack**

- Updated **Stack** algorithm. It now works better for single polygonal rectangular islands.
- Fixed a bug with **Copy/Paste** operators when working with multiple objects.

#### **Texel Density**

- Added **Texel Density Presets** system.
- Added **Select by TD** operator.
- Updated **Texel Density Display** algorithm.
- Fixed a bug with automatic vertex color map activation.

#### **Transform**

- Added **Arrange** operator to **Distribute** tool for grid distribution of islands.

#### **Preferences**

- Added **Update** operator to avoid possible errors when updating the add-on.
- Added **Unregister Zen UV Core** operator to disable the external module.
- Added the possibility to change the **Sticky UV Editor** button position.
- Updated **Sticky UV Editor** to work in ****Blender 3.0.
- Updated **Zen UV Keymaps** operator. It now opens a window with a full list of hotkeys instead of the global Keymap.