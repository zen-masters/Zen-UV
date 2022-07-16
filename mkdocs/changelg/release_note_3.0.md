# Version 3.0

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/C6CABQyTIK8" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br>

## General

- Added Relax operator. This is a new unwrapping method that is well suited for working with organic models.
- Added World Orient operator that rotates Islands the way they are oriented in the model.
- Added Reshape Island operator which changes Island depending on the preset (Selected, U/V Direction, Borders). 
- Added Copy UV / Paste UV operators to transfer UV coordinates between UV Maps.
- Added Blender 3.2 support.

## UI

### Main Menu

 - Added Advanced UV Maps panel to UV Editor.
 - Changed appearance of Transform panel. Operators independent of Island/Elements settings have been moved to the top of the panel.

### Pie Menu

 - Added Relax operator (section 1).

## Operators

### Advanced UV Maps

- Added Advanced UV Maps panel to UV Editor.
- Added options to specify UV Map name template.
- Added Copy UV / Paste UV operators to transfer UV coordinates between UV Maps.
- Added Unwrap Modes when creating a new UV Map (Default, Smart, Cube, Cylinder, Sphere).
- Fixed a bug when creating a new UV Map.

### Seams Groups

- Fixed a bug when assigning Seams without an active group. 

### Unwrap

- Added ability to work in Mark System not only with global properties but also with local ones.
- Added Mark Sharp by UV Borders operator.
- Added options to clean up existing Seams for Mark Seams by UV Borders operator.
- Improved performance of Mark by Angle operator.
- Fixed a bug that caused the UV map to be destroyed when changing UV coordinates when the Display - Finished was enabled.

### Select

- Added Select UV Borders operator.
- Added Select Edges By Direction operator. (Blender 3.2 only)
- Fixed a bug in UV Sync Off mode for Select Similar operator.


### Checker Map

- Added ability to tile checker texture for Material Preview and Rendered display modes.
- Added checker texture to check Islands orientation.
- Fixed automatic updating of the texture in UV Editor when the checker is enabled.
- Fixed a bug when switching if the material has multiple Material Output.

### Texel Density

- Fixed a bug setting Texel Density for islands with zero areas.
- Fixed a bug in working with Instances.
- Optimized value accuracy.

### Transform

- Added Relax operator. This is a new unwrapping method that is well suited for working with organic models.
- Added integration with Zen Sets addon. Used to display Island Mesh Errors in Relax operator.
- Added World Orient operator that rotates Islands the way they are oriented in the model.
- Added options for orienting Islands in Quadrify operator (Horizontal/Vertical).
- Added Average Texel Density option for Quadrify operator.
- Fixed a bug with the Quadrify operator when working with several objects when Islands were not processed and increased significantly in size.
<br> <br>
- Added Reshape Island operator which changes Island depending on the preset. 
    - Selected. Aligns selected Edge Loops and relaxes unselected vertices. 
    - U/V Direction. Aligns Edges located in the corresponding direction.
    - Borders. Aligns edges into straight lines according to the given criteria.
<br> <br>
- Updated Scale operator, the input method of initial data is divided into two modes.
    - Axis. Default mode with new Values Tuner to quickly change settings.
    - Units. The mode in which you can set Scale based on the estimated size of the UV area.
<br> <br>
- Added Fit into Region operator for locating Islands in a given region with the ability to capture  Region Size from Selected Islands/Vertices.

- Fixed a bug with the Fit operator when working with islands with zero thickness.
Stack
- Added options for shifting islands for Stack operator.
- Added Stack Collect Mode Simple (Simple Stack, Simple Unstack).
- Added ability to work between UV Maps for Copy/Paste operators.
- Added Paste operator options (Stack Offset, Keep Proportion).
- Fixed a bug with the Paste operator in polygonal mode.
- Fixed bug of Paste operator with Transfer mode if Islands are the same.

### Sticky UV Editor

- Added the ability to remember Pivot settings in UV Editor.
- Added option to open widget properties (Ctrl+Shift+LMB on the Sticky UV icon).
- Fixed a bug when the Sticky UV Editor widget does not work in combination with Alt.
- Fixed a bug with closing windows.

### Preferences

- Added a button to download the Zen Core library.
- Added a list with all Zen add-ons.
- Added ability to assign Modifier Key to call alternative commands in the interface.
- Improved add-on update system. Added recommendations and filters when selecting a file.
