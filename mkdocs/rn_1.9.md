## Version 1.9 (Texture Checker)

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/w8o4TVW_VuM" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br><br>

### General

- **Zen UV now works with multiple objects!**
- Added **Finished System.** It helps to control and manage the state of unwrapping UV Islands (Finished/Unfinished) by tags and visually. Nothing will be left not unwrapped!
- Updated **Checker System.** Now it is based on nodes and contains textures designed specifically for Zen UV. Custom textures can be added easily by the user at the node level.
- Added **UV Maps Properties Tab** to have quick access to UV Maps management.
- Updated **Quadrify** operator. Now it is based on the native **Follow Active Quad** operator and sets the base polygon size based on the average size of current islands.
- **Redesigned UI** to support current and all new updates.

### UI

#### **Main Menu**

- The interface has been completely redesigned and operators have been classified and divided into the following groups:

Operator | Function
:---|:---
    **UV Maps**  |          Selecting and managing UV maps. 
    **Unwrap**    |           Marking and unwrapping operations.
    **Select**   |               Edges/Islands selection operations.
    **Pack**      |               Pack operations.
    **Checker Map**   |   Display control of Checker textures.
    **Preferences**    |     Hotkeys and other general settings.
    **Help**            |        Documentation and support section.


- Operators options were hidden under the **Settings icons** to optimize space.

#### **Pie Menu:**

- Alternative **CTRL** operators **Pin/Unpin Islands** were replaced by **Tag Finished/Unfinished** from the new powerful **Finished System**. (Sector 4 and Sector 6).
- Added new alternative **CTRL** operator **Select Flipped Islands** to **Select Islands** (Sector 7).
- Added icons for **Quadrify Islands** and **Checker Texture (Toggle)** operators.

#### **Pop Up Menu:**

- All operator options were removed from the Pop Up menu, you can adjust them only in the Main menu. The order of operators is consistent with the Main menu.

### Operators

#### **UV Maps**

- Added **UV Maps Properties Tab** to have quick access to UV Maps management.

#### **Unwrap**

- Added **Tag Unwrapped** option for **Zen Unwrap** operator.
- Added **Sort Unwrapped** option for **Zen Unwrap** operator.
- Added **Auto UV Sync** option for **Zen Unwrap** operator.
- Added **Unwrap Method** option for choosing Unwrap algorithm.
- **Zen Unwrap** now is using the packing algorithm selected in **Pack Engine**.
- Added a warning for the **Marking System** when both **Mark Seams** and **Mark Sharp Edges** options are off.
- Fixed **Smooth by Sharp (Toggle)** operator**.** Now its use ****does not require re-switching.
- Added **Finished System**. It has absorbed **Pin System** and was made to control and manage the state of unwrapping UV Islands (Finished/Unfinished) by tags and visually. Tags can be assigned manually or automatically after unwrapping. Islands can be sorted and pinned by state in UV Editor. You can check the state of Islands in the viewport by using **Display Finished (Toggle)** operator. Nothing will be left not unwrapped!
- Updated **Quadrify** operator. Now it is based on the native **Follow Active Quad** operator and sets the base polygon size based on the average size of current islands.

#### **Select**

- Updated **Isolate Islands (Toggle)** operator. Isolation mode now is working for any selection mode — Vertex/Edge/Polygon. It no longer requires you to select at least one Vertex/Edge/Polygon in order to return back.
- Added **Select Flipped Islands** operator.
- Added **Select Sharp Edges** operator.
- Added **Select Seam Edges** operator.
- **Select Edge Loop** operator ****name ****was changed to **Select Interseam Loop**.

#### **Pack**

- Added **Rotate Islands** option for **Pack Islands** operator.

#### **Checker Map**

- Updated **Checker System**. Now it has 2 types of texture checker - color and monochrome. Each type has 4 sizes. Custom textures can be added easily by the user at the node level.. The **Reset Checker** operator will return the **Checker System** to its initial state.
- Added **Show Image In UV Editor** option. It allows you to turn off the display of texture in the UV Editor.
- Added **Remove Checker Nodes** operator. It removes all checker nodes from the scene to not interfere with the export.

#### **Preferences**

- **Reset Preferences** now returns Auto Mark operator angle settings to their default values.

#### **Help**

- Added information about the current Zen UV version number at the end of the section.