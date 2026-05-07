# Operators

!!! Info
    ## ZenUV 3 Support Status

    We would like to inform you that the documentation available on this web page pertains exclusively to Zen UV 3.

    ### ZenUV 3 Support Notice
    Please be advised that active development and technical support for **ZenUV 3** have officially concluded. This version is fully compatible with Blender up to version **5.0**.

    We understand that many of you rely on ZenUV for your professional workflows, and we sincerely apologize for any inconvenience this transition may cause. While we have always strived to provide long-term value, the one-time fixed price paid for ZenUV 3 is no longer sufficient to cover the extensive amount of work required to maintain compatibility with the rapidly changing architecture of newer Blender versions. To ensure the project remains sustainable and continues to meet high standards, we must focus our resources on the next generation of the addon.

    ### Discover [ZenUV 5](https://zenmastersteam.github.io/Zen-UV/latest/)
    To take full advantage of the latest advancements in Blender and UV mapping technology, we strongly recommend upgrading to [**ZenUV 5**](https://superhivemarket.com/products/zen-uv).

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
Straighten rectangular-shaped UV Islands.

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

*Select at least one edge/face of the Island(s).*

## Isolate Islands (Toggle)
Isolate UV Islands (Toggle). 

*Select at least one edge/face of the Island(s).*


## Select Overlapped Islands
Select Overlapped Islands.

*Works in Blender 2.81 and above.*

## Select Edge Loop
Select edge loops with Seams respect.

## Pin UV Island
Pin UV Island. 

*Select at least one edge/face of the Island(s).*

## Unpin UV Island
Unpin UV Island. 

*Select at least one edge/face of the Island(s).*

## Show Pinned Islands (Toggle)
Show Pinned Islands (Toggle).

## Checker Texture (Toggle)
Add Checker Texture to the mesh (Toggle).

## Smooth Mode (Toggle)
Toggle between Auto Smooth 180° (with sharp edges) and regular smooth modes.