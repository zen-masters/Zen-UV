## Version 1.8

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
<iframe src="https://www.youtube.com/embed/yZ-rRiE-8us" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen="" seamless="" frameborder="0"></iframe>
</div>
<br><br>

### General
- Added Selected Only option to Zen Unwrap. It’s a separate workflow where only Selected Faces will be Unwrapped and Packed. It includes warnings and Unwrapping options if nothing is selected.
- Added Islands Offset option to Zen Unwrap. It’s available after activating Selected Only. Adds the ability to move inactive islands in the UV viewport to the left when working with the Zen Unwrap operator.
- Auto Seams changed to Auto Mark. Zen UV now marks both Sharp Edges and Seam Edges. What exactly to mark can be configured in the panel using Mark Seams and Mark Sharp Edges checkboxes. This means that with Zen UV you can not only map, but also use it exclusively for the Sharp Edges marking.
- Auto Mark now has the possibility to change the angle. Works in interactive mode.
- Added Mark Seams by Sharp Edges option.
- Added Mark Sharp Edges by Seams option.
- Added Pack After Quadrify option which automatically Pack Islands after Quadrify Islands operation.
- Added Pack Islands option. Also can be found in the Pie menu as an alternative command in sector 9 (Zen Unwrap).
- Added Margin option which allows setting space between Islands for Pack Islands operation.
- Added Average Islands Scale option which averages Islands scale before Pack Islands operation.
- Added the possibility to choose Pack Engine.
- Added option to use UVPackmaster 2 Pack Engine if it’s installed on the system.
- Added Select Edge Loop option which allows selecting edge loops with Seams respect.
- Added Auto Fit UV View option which automatically Fit and Zoom UV viewport.
- Added Show Bevel Weight and Show Crease Edges options due to the probability of overlapping displayable edge types.
- Added the Reset Preferences button to reset all the settings to the default state.
- The addon preferences moved from the scene properties to the addon properties. This allows remembering settings between sessions.
- Fully reworked Main and Popup menus, structure, and design.
- Fixed the loading icons bug that occurs on some systems.