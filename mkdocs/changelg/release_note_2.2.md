## Version 2.2

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/CuFHQpDHBj0?list=PLWaOMtLS0nN2ZA_5id0FNbPTu0s_XNT3o" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br><br>

### General

- Added the **ability to use Transform tools for elements** (vertices, edges, polygons).
- Added **Sticky UV Editor** - tool for quick access to UV Editor.
- Added **Display Stretch Map** operator for UV distortion control.
- Added **UV-Packer support**.

### UI

#### **Main Menu**

- Redesigned **Mark panel**.
- Redesigned **Select panel**.
- Redesigned **Finished System panel**.
- **Quadrify** operator has been moved to the **Transform section**.

#### **Pie Menu**

- Added **Display Stretch Map** operator (section 3).
- Added **Straight Islands** operator (section 1).

### Operators

#### **Unwrap**

- Added **Live Unwrap** functionality to **Mark / Unmark** operators.

#### **Pack**

- Added **UV-Packer** support.
- Fixed a bug when **UV Pack To Other** in UVP2 Pack Engine led to a error.

#### **Checker Map**

- Added **Display Stretch Map** operator for UV distortion control. It also allows you to select distorted Island.
- Fixed a bug when Checker Texture created copies of textures in the form of data blocks

#### **Transform**

- Added the ability to work with elements (vertices, edges, polygons).
- Added **To UV Area** option for **Align** operator, you can Align the Island to the edge of the UV zone.
- Added **Distribute & Sort** operator to distribute and sort Islands according to different criteria.
- Added **Straight Islands** operator to align vertices in a straight line.
- Added **Randomize** operator for randomizing Islands position.
- Updated **2D Cursor mode**, if nothing is selected, the cursor moves to the edges of the UV zone.
- Updated **Quadrify Islands** operator. Added option to align the Island along the coordinate axes.
- Updated **Quadrify Islands** operator. Added option to unwrap polygons that are not quads. They are not included in the Island, but get the correct unwrapping as a separate Island.
- Fixed Transformation name in the Undo list.
- Fixed a bug with **Flip** operator in Pivot - Individual Origins mode.

#### **Preferences**

- Fixed a bug with disabling **Select panel**.

---
## Version 2.1.3
### Operators

#### **Seam Groups**

- Fixed a bug in Seam Groups operators when working with multiple objects.

#### **Unwrap**

- Added functionality to Zen Unwrap operator for marking in switch mode. This allows you to use an operator similar to Blender's native Live Unwrap option.
- Fixed a bug when using Mark operators when marking the first seams on an object.

#### **Pack**

- Fixed Lock Overlapping Mode - Any Part parameter for UVP2 Pack Engine.
- Fixed a delay when working with UVP2 if Heuristic mode is activated.
- Fixed a bug when UVP2 runs in demo mode. Added warning.

#### **Stack**

- Added Remove All operator to remove all Manual Stack for selected objects.
- Fixed a bug in Manual Stacks when working with multiple objects.
- Fixed a bug in the Copy / Paste system when working with multiple objects.

#### **Texel Density**

- Added Set to Checker operator for transferring Сurrent TD values to TD Checker.
- Added displaying units next to the Current TD display field.
- Fixed a bug in TD Checker operator when working with multi-user mesh.