# Version 3.1


## General

- Improved Zen Unwrap operator. All settings are moved to a separate menu. Added Unfold Vertices and Seams Switch modes.
- Added Excluded system for the Pack operator. Mark Islands to exclude them from packing. This works for Blender Pack and UV Packmater Engine.
- Added Mac M1 Support for Zen Core and Relax libraries (Silicon app).

## UI

### Main Menu

 - Disabled panels in UV Editor context in Object mode.

### Pie Menu

 - Added the ability to disable Pie Assist.
 - Added the ability to change Pie Assist font size.
 - Fixed a bug where the Pie menu was not disabled after an operator call.


## Operators

### Advanced UV Maps

- Added options to disable numbering, rename only the active map, and use the default name.

### Seams Groups

- Fixed a bug with processing renamed groups.

### Unwrap

- Improved Zen Unwrap operator. All settings are moved to a separate menu. Added Unfold Vertices and Seams Switch modes.
- Fixed a bug with Select Finished highlighting all polygons if Clear is on.
- Fixed incorrect warning output for Unmark operator.

### Select

- Added Select by UV Area operator to select polygons and Islands by area.
- Added an option to ignore Area for Select Similar operator.
- Fixed a bug with selection for Select Similar operator. for Blender 3.2 and above.
- Fixed a bug with selecting invisible islands in Sync UV Off mode for Blender 3.2 and higher.

### Pack

- Added Excluded system for the Pack operator. Mark Islands to exclude them from packing. This works for Blender Pack and UV Packmaster Engine.
- Improved work with UV Packmaster Engine. Added the ability to display Overlay Info.

### Checker Map

- Added the ability to select a texture for Texture Checker in the context of UV Editor. By default, the Texture Checker panel in UV Editor context is disabled.
- Added the ability to restore the viewport display mode when switching the Checker Texture.
- Fixed a bug with a possible inconsistency between the state of the texture filtering button and the state of the texture.

### Transform

- Added option Tag as Finished for Quadrify operator.
- Added options for direction and sort by location in 3D space for Distribute operator.
- Added position option for Align operator. Now you can specify any position and position Islands relative to it.
- Fixed a bug with incorrect scaling during Fit into Region operation.
- Fixed bug functionality in Pivot - Individual Origins. Mode - Elements. mode. for Fit operator.

### Sticky UV Editor

- Fixed a bug when the widget did not work while the file was being saved.
- Fixed a bug when the widget did not work when using the stylus.

### Preferences

- Fixed bug with Reset Preferences operator.
