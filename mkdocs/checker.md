# Checker Map

![Checker Map](img/screen/checker.png)

!!! Panel
    ![Main Panel](img/screen/tex_checker/checker_main_panel.png)

    - The panel in 3D Viewport has a full set of features.

!!! Panel
    ![Main Panel](img/screen/tex_checker/checker_uv_panel.png)

    - The panel in the UV Editor has a minimal set of functions. And serves only to change the checker texture. This panel is disabled by default. You can turn it on in the addon settings.

### Checker Texture (Toggle) ![Checker Texture](img/icons/checker_32.png)

Add Checker Texture to the mesh (Toggle).

!!! Preferences
    ![Main Panel](img/screen/tex_checker/tex_chk_props.png)

    - **Checker Library Folder** - Checker Library Folder indicates the folder with 
    which Zen UV Checker will work.
        All textures in * .JPG, * .PNG formats that are 
        inside this folder will be collected in 
        Checker Textures list and can be used to display 
        on selected models.
    - **Reset Folder** - Reset Checker Library path to Default State.
    - **Load Your Texture** - Open File Browser and add the selected texture to the Checker Library.
    - **Refresh Texture Library** - Refresh Textures from Checker Library Folder.
    - **Auto Sync Checker** - Automatically sync selected Checker Texture with Viewport.
    - **Open Shader Editor** - Open Shader Editor with Zen UV Checker Node.
    - **Reset Checker** - Reset Zen UV Checker to Default state.

### Remove Checker Nodes

- Remove Zen UV Checker Nodes from the scene materials.

### Checker Textures Selector

![](img/screen/tex_checker/chk_filter_interpolation.png)

#### 1. Interpolation ![](img/screen/tex_checker/ico_interpolation.png)

- Switch texture interpolation in the Checker Node between Linear and Closest.
  
![](img/screen/tex_checker/interp_differences.png)

#### 2. Checker Textures

- The Checker Textures field is used to select the checker texture that will be displayed on the selected models.
- A full list of default textures.

![](img/screen/tex_checker/chk_textures_full_list.png)

- Any texture can be tiled or offset but only in the Material Preview or Rendered modes.

![](img/screen/tex_checker/m_prev_offset_modes.png)

![](img/screen/tex_checker/chk_tiling_offset.png)

- Every texture has an bright green pixel in U = 0, V = 0 coordinates.
- If you see green faces - keep in mind that they do not have UV coordinates.
  
![](img/screen/tex_checker/magic_pixel.png)

#### 3. Filter ![](img/icons/checker-Filter_32.png)

- Enable resolution fields to filter existing textures by X or/and Y resolutions.
- Includes a Lock button for filtering square format textures.
- Includes an "O" button for activating Orient Checker texture.

![](img/screen/tex_checker/filter_is_on.png)

- Orient filtering is on.
  
![](img/screen/tex_checker/filter_orient_is_on.png)

### Display Stretch Map

- Display an angle-based stretching map.

![](img/screen/tex_checker/stretch_map_sample.png)

  1. Toggle displaying of the stretch map.
  2. Select stretched faces.