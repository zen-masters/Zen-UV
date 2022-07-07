## Version 2.0 (Transform)

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/Y7dG2i-FASs" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br><br>
### General

- Added **Hard Ops add-on integration.** It allows **displaying UV manipulations in 3D View.**
- Added **Seam Groups category.** You can now work with more than one Seam set.
- Added **Transform category.** Move, Rotate, Scale, Flip, Fit, Orient and Align islands.

### UI
#### **Main Menu**
- Added panels management. Now you can disable displaying unused categories.
  
### Operators
#### **Unwrap**
- Added **By selected Edges** option to Quadrify Islands operator. It allows automatically mark selected Edges as Seams.
- Added **Mirror Seams** operator.
- Fixed **Mark By Angle** operator. Now it ignores hidden edges.
#### **Checker Map**
- Fixed the logic of switching the display of **Display Finished (Toggle)** and **Checker Texture (Toggle)** operators.
#### **Pack**
- Added possibility to specify **Margin in pixels.**

#### **Texel Density**
- Fixed **Show TD** operator. Now it doesn't show an error if objects other than the MESH type are selected.
- Fixed **Set TD** operator Now it works right with islands if the object has a scale different from (1,1,1)
