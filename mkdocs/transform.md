# Transform System

!!! Panel
    ![Transform](img/screen/transform/tr_main_panel.png)

---
## Independent Transform Operators:
---
### Relax ![](img/icons/relax-1_32.png)

 - Allows to reduce the stretching the faces of the island. Uses three algorithms.
     - **Zen Relax** - The algorithm is most suitable for organic objects.
     - **Angle Based** - Blender's native algorithm. Most suitable for the hard surfaces objects.
     - **Conformal** - Blender's native algorithm. Same as **Angle Based**, but much faster. However, can lead to undesired results if the island is complicated.

![](img/screen/transform/relax.png)

---
### World Orient.

 - Rotate Islands the way they are oriented on the Models. Each method (Organic/Hard Surface) uses a heuristic approach and correctly orients most of the Islands in its area.
  
  ![](img/screen/transform/world_orient_props.png)

 - **Method: Hard Surface / Organic** - The orientation method is suitable for geometry types.
 - **Further orient** - Additional turn. Allows you to turn the island to a horizontal or vertical if the island is located at an angle in the model.
 - **Flip By Axis** - Allow changing direction of the island after basic orientation. Suitable if needed change orientation from legs to head for example.

---
### Randomize.
 - Randomize the position, rotation, and scale of the islands or selected vertices.

 ![](img/screen/transform/randomize.png)

---
### Quadrify Islands ![](img/icons/quadrify_32.png)

Straighten rectangular-shaped Islands.

![](img/screen/transform/quadrify_op_props.png)

!!! Preferences

    - **By selected Edges** - Selected Edges will be used and marked as Seams during Quadrify Islands operation. Works only in edge selection mode.
    - **Mark Borders** - Mark borders as seams/sharp after Quadrify Island operation.
    - **Mark Seams** - Mark seam in case **Mark Borders** is on.
    - **Mark Sharp** - Mark sharp in case **Mark Borders** is on.
    - **Orient to: ** - How to orient Quadrified Islands.
      - **Initial** - Leave orientation as is.
      - **Vertical** - Set orientation vertical.
      - **Horizontal** - Set orientation horizontal.

    - **Average Texel Density** - Averaging the size for the processed islands.

    - **Pack Quadrified** - Pac Islands after Quadrify Islands operation.
    - **Pin Quadrified** - Pin Islands after Quadrify Islands operation.

---

### Reshape Island

Changes the island’s shape depending on the preset. [Here is full information](operators/reshape_island.md) about Reshape Island.

- **Selected** -  Straighten the selected Edge Loops and relax not selected vertices.
- **U Direction / V Direction** - Edges is aligned in the indicated direction.
- **Borders** - Straighten the edges of the island in even lines according to the given parameters.

![](img/screen/transform/reshape_presets_collected.png)

---
## Unified Transform System:
!!! Panel
    ![](img/screen/transform/tr_un_tr_sys.png)

### Universal Control Panel

!!! Control
    **Universal Control Panel**

    ![Transform](img/screen/transform/UniversalControl.png)

    The universal control panel has logic and different functions for different types of transformation.

---
### Pivot.

 - The pivot of transformation.

![](img/screen/transform/tr_un_pivot.png)

### Mode.

 - The Mode of transformation. In the Elements mode transformation will be performed over vertices, edges, and faces.

![](img/screen/transform/tr_un_mode.png)

---
## Transform Types:

### Transform type Move. ![](img/icons/transform-move.png)

![Transform](img/screen/transform/MainPanelMove.png)


!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **Move** represent the direction of shifting.

#### Move Increment
 - The value on which the island will be shifted.

---
### Transform type Scale. ![](img/icons/transform-scale.png)

![Transform](img/screen/transform/tr_scale.png)

!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **Scale** represent Points from where the island will be scaled.

#### Scale Mode:

![](img/screen/transform/tr_scale_modes.png)

#### Mode - **Axis**.

![](img/screen/transform/tr_scale_mode_axis.png)

 - **Scale** - The value of the scale of the island for each of the axes.
 - **Tuner** - System that helps change values quickly.
     - "D" - Increase by two times.
     - "H" - Decrease two times.
     - "R" - Reset value to 1.0 .
     - Lock. - The Lock mode allows changing values as one.

#### Mode - **Units**.

![](img/screen/transform/tr_scale_mode_units.png)

 - **UV Size** - The estimated width of the UV area.
 - **Desired size** - The size of which should be set for selected elements relative to UV area.
 - **G** - Grab desired size from current selection. Exist only in the 3D Viewort context. Can be used only for 2 vertices or for one edge selection.
 - **Horizontal / Vertical** - What mean the Desired Size.

---
### Transform type Rotate. ![](img/icons/transform-rotate.png)

![Transform](img/screen/transform/Rotate.png)


!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **Scale** works as described. Buttons located in the corners rotate the island in the specified direction.
    The central button performs the automatic aligning of the island horizontally or vertically. The buttons at the top and bottom align the island vertically. Buttons on the left and right align the island horizontally.

#### Rotate Increment
 - The value on which the island will be rotated.
#### Orient by selected
 - Reorient the island by selected elements (vertices, edges, polygons).

---
### Transform type Flip. ![](img/icons/transform-flip.png)

![Transform](img/screen/transform/Flip.png)

!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **Flip** represent flip direction.

---
### Transform type Fit. ![](img/icons/transform-fit.png)

![Transform](img/screen/transform/Fit.png)

Fit island to UV Square.

!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **Fit** represent origins from where **Fit** will be performed.

#### Fill Islands

 - Fit Islands from Center without keeping proportions.

#### Padding

 - Clearance between island and UV Square bounds.

#### Bounds

 - It makes it possible to fill out not UV Square but any other area.

### Fit into Region.

![](img/screen/transform/fit_into_region.png)

 - **Grab Region: Selection / Island** - Allow to grab Region size in different manners.
 - **Bottom Left: Top Right:** - The bounding box of the region.
 - **Fit into Region** - Fit selected island in to the Region described in the bounding box.

---
## Transform type Align. ![](img/icons/transform-orient.png)

![Transform](img/screen/transform/Align.png)


!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **Align** represent the side by which the islands will be aligned.

### To UV Area Bounds
 - Allow aligning current selection to the UV Area bounds.

---
## Transform type Distribute. ![](img/icons/transform-distribute.png)

![Transform](img/screen/transform/Distribute.png)

### Islands Mode

 - **Distribute & Sort** - Distributes and Sorts the selected islands.
 - **Arrange** - Arrange the selected islands.

### Elements Mode

 - **Distribute** - Distribute vertices along the line.


---

# Transform type 2D Cursor. ![](img/icons/transform-cursor.png)

![Transform](img/screen/transform/2dCursor.png)

Align 2D Cursor over the selected island.

!!! Info
    - Buttons of the [**Universal Control Panel**](#universal-control-panel) in the Transform type **2D Cursor** represent sides of the island or selected elements.

