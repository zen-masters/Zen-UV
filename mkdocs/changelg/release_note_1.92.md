## Version 1.92 (Texel Density)

### General

- **Zen UV now works** not only in Edit Mode but also **in Object mode**. The following functions are available in Object Mode: Advanced UV Maps, UV Coverage, Checker Map, Texel Density Checker.
- **Added Texel Density category.** Get, Set, and Check Texel Density of UV Islands.
- Updated **Checker Map category**. Add your own textures, filter existing textures by resolution, square and rectangular formats.
- Updated **UV Maps category**. Now you can work on UV Maps of the selected objects in sync.

### Operators
#### **Advanced UV Maps**

- Added **Sync UV Maps operator.** Now you can duplicate, remove, clean and rename UV Maps of the selected objects in sync.
- Added **Rename UV Map** operator with pattern UV_Channel_* to keep the right order of UV Maps during export.
  
#### **Unwrap**

- Fixed **Zen Unwrap** operator. Now it ignores Islands tagged as Finished.
- Updated **Quadrify Islands** operator. Islands with the same geometry get the same unfolding.

#### **Pack**

- Added **UV Coverage** operator. It helps to determine the percentage of UV Map coverage.

#### **Checker Map**

- Added **Filters** to filter existing textures by resolution, square and rectangular formats.
- Added the possibility to add custom Checker textures and texture libraries.