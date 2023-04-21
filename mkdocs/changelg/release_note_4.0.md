# Version 4.0

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/A33NDMoRChM" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br>


## General

### New Systems
- Added **Compact UI system**. One panel to rule them all! 
- Added **Trimsheet system**. Create Trimsheets and Move, Rotate, Scale, Fit, Align and Flip Islands inside Trims.
- Added **Zen UV Transform tool**. Move, Rotate, Scale, Fit, Align and Flip Islands in 3D View and UV Editor using **Zen UV Gizmo**.

### New Operators
- Added **Display Flipped** operator to display Flipped Islands in UV Editor.
- Added **Unwrap Constraint** operator to unwrap Islands along a certain axis.
- Added **Match and Stitch** operator to match Islands position, rotation, scale and stitch vertices if it’s possible.

## Operators

### Unwrap
- Added **Unwrap Constraint** operator to unwrap Islands along a certain axis. 
- Added the ability to save existing Seams for **Unwrap by Angle** operator.
- Added the ability to create Seams only for selected edges for **Unwrap by Angle** operator.
- Fixed a bug with incorrect separation of Marked edges.
- Fixed a bug with edge marking if it is disabled in Global mode for Zen Unwrap operator.

### Select
- Added the ability to work in UV Editor in Sync UV Off mode for **Select Interseam** operator.
- Fixed a bug with incorrect selection with Sync UV Off mode for **Select Flipped** operator.

### Transform
- Added **Match and Stitch** operator to match Islands position, rotation, scale and stitch vertices if it’s possible.
- Added **Advanced Transform** operators to make it easier to assign Transform operators to hotkeys.
- Added the ability to Distribute Islands based on their location in UV space (UV Position) for **Distribute and Sort** operator.
- Added **Move to UV Area** operator to move Islands to the main UV Area preserving UVs.
- Added the ability to stick Islands position and size after Relaxing.
- Fixed a bug where selected edge did not split Island for **Quadrify Island** operator.
- Fixed a bug with transformation for non-square textures.
- Fixed a bug with Multi object selection in **World Orient** operator.

### Texel Density
- Improved Texel Density preset system, now it works with Blender's native preset system.
- Fixed a bug with getting TD from very small Islands.

### Checker Map
- Added **Display Flipped** operator to display Flipped Islands in UV Editor.
- Added Select operators to detect mesh errors.
- Added previews to the list of checker textures.
- Added some elements to the panel in the UV Editor context.
- Fixed a bug of z-fight system for Blender 3.0 and above.
- Fixed a bug if there is an empty group in the nodes.

### Pack
- Added the ability to **Pack Islands into active Trim** (UVP only).
- Added the ability to **Pack selected Islands**. Allows you to pack only selected Islands (except UV Packer).
- Fixed a bug with UVP Engine. Overlay output conflict if HOps UV Display is On.

### Preferences
- Added the ability to disable Progress Bar.

### Sticky UV Widget
- Fixed a bug with closing the last UV Editor if there are no other editors in the layout.

### Other
- Added **Darken Image** operator in Overlay to darken texture in UV Editor.
- Stopped support for Blender versions lower than 2.93