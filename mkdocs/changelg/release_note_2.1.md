Version 2.1 (Stacks)

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/Yj2SecY-c1Y" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br><br>

### General

- Added **Stack** category. **Stack** and **Unstack** islands automatically and manually. Extremely useful for increasing Texel Density and baking. It works using **Zen UV Dynamic Library** supported on Windows, Mac OS, and Linux platforms.
- Added **Copy/Paste** operators. Copy parameters (TD, Position, Size) between Islands.

### UI

#### **Main Menu**

- Added new operators for UV Editor window.
- Added panels management for UV Editor window. Now you can turn off the display of unused categories not only in 3D View but in UV Editor also.
- Fixed slowdown of the Main panel when working with large (~500,000 polygons) meshes.

### Operators

#### **Advanced UV Maps**

- Fixed a bug with disabling **Advanced UV Maps** panel when Cycles render is selected.

#### **Unwrap**

- Added **Mark Seams By Open Edges** operator. Mark all visible Edge Borders as Seams.
- Fixed **Zen Unwrap** operator. The situation when it is impossible to unite two islands, one of which is tagged FINISHED and the other UNFINISHED.
- Fixed **Mark Seams by UV Borders** operator. It now ignores hidden edges.
- Fixed **Mirror Seams** operator.
- Updated **Display Finished** operator. It now uses OSL Shaders instead of Vertex Color and can display Finished Islands and Checker textures simultaneously.
- Updated **Quadrify** operator. The processing time has been significantly reduced.

#### **Select**

- Added **Select Similar Islands** operator.
- Fixed **Select Flipped Islands** operator. It now handles n-gons correctly.
- Updated **Isolate Island** operator. It now works in any Blender UV Sync mode. Now you can use it not only in 3D View but in UV Editor also.

#### **Checker Map**

- Fixed a bug when **Reset Checker** operator did not restore the texture.
- Updated **Checker Texture (Toggle)** operator. It now uses OSL Shaders instead of Vertex Color and can display Checker Texture and Finished Islands simultaneously.

#### **Pack**

- Added **Keep Stacked** parameter.

#### **Texel Density**

- Added the possibility to measure and set **Texel Density in Object mode**.
- Updated **Texel Density** operators. The processing time has been significantly reduced.