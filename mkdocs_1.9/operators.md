# Operators

## Zen Unwrap ![Zen Unwrap](img/icons/zen-unwrap@2x.png)
Unwrap by Marked edges and Pack after. Also, you can select edges/faces and do Zen Unwrap. All selected edges/faces will be Marked as Seams and/or Sharp edges and unwrapped after.

!!! Preferences
    #### Auto Mark with Zen Unwrap
    - Automatically Mark edges by angle for Zen Unwrap.

    #### Selected Only
    - Separate workflow where only Selected Faces will be Unwrapped and Packed. It includes warnings and Unwrapping options if nothing is selected.

    #### Islands Offset
    - Offset Islands after Zen Unwrap. (Experimental).

## Auto Mark
Automatically Mark edges as Seams and/or Sharp edges.

## Mark ![Mark](img/icons/mark-seams@2x.png)
Mark selected edges or face borders as Seams and/or Sharp edges.

## Unmark ![Unmark](img/icons/unmark-seams@2x.png)
Unmark selected edges or face borders as Seams and/or Sharp edges.

## Unmark All
Remove all the Seams and/or Sharp edges from the mesh.

!!! Preferences
    #### Mark Seams
    - Automatically assign Seams.

    #### Mark Sharp Edges
    - Automatically assign Sharp edges.

## Mark Seams by UV Borders
Mark Seams by existing UV Borders.

## Mark Seams by Sharp Edges
Mark Seams by existing Sharp edges.

## Mark Sharp Edges by Seams
Mark Sharp edges by existing Seams.

## Quadrify Islands
Straighten rectangular shaped UV Islands.

*The addon is using the [quadrification algorithm](https://github.com/Radivarig/UvSquares) by Radivarig.*

!!! Preferences 
    #### Auto Pin Quadrified
    - Automatically Pin Islands after Quadrify Islands operation.

    #### Pack After Quadrify
    - Automatically Pack Islands after Quadrify Islands operation.

## Pack Islands
Pack all Islands.

!!! Preferences
    #### Margin
    - Set space between Islands for Pack Islands operation.

    #### Average Islands Scale
    - Average Islands scale before Pack Islands operation.

    #### Pack Engine
    - Select Pack Engine for Pack Islands operation.

    *The add-on is using the Blender Pack algorithm or [UVPackmaster 2 Engine](https://gumroad.com/l/uvpackmaster2) by glukoz.*

## Select Islands
Select UV Islands. 

*Select at least one edge/face of the Island(s)..*

## Isolate Islands (Toggle)
Isolate UV Islands (Toggle). 

*Select at least one edge/face of the Island(s)..*


## Select Overlapped Islands
Select Overlapped Islands.

*Works in Blender 2.81 and above.*

## Select Edge Loop
Select edge loops with Seams respect.

## Pin UV Island
Pin UV Island. 

*Select at least one edge/face of the Island(s)..*

## Unpin UV Island
Unpin UV Island. 

*Select at least one edge/face of the Island(s)..*

## Show Pinned Islands (Toggle)
Show Pinned Islands (Toggle).

## Checker Texture (Toggle)
Add Checker Texture to the mesh (Toggle).

## Smooth Mode (Toggle)
Toggle between Auto Smooth 180° (with sharp edges) and regular smooth modes.