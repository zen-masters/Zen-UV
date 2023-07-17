# Stack

!!! Info
    We would like to inform you that the documentation available on this web page pertains exclusively to Zen UV 3. However, we would like to emphasize that [**Zen UV 4 is now available and offers a significantly improved user experience**](https://zenmastersteam.github.io/Zen-UV/latest/).

    We also remind that Zen UV 3 users can [**Upgrade Zen UV 3 to Zen UV 4 with a discount!**](https://zenmastersteam.github.io/Zen-UV/latest/zenuv3_to_zenuv4/#upgrade-zen-uv-3-to-zen-uv-4-faq)

!!! Panel
    ![Stack](img/screen/stack/stack.png)

## Stack

Collect Similar Islands on Stacks.

!!! Properties
    ![Stack](img/screen/stack/stack_options.png)

    - **Move Only** - Don't fit Islands. Just move to the same position.
    - **Stack Offset** - The offset value. Can be used for preventing auto merging the UV vertices.
    - **Unstack Direction** - The Direction where the island will be shifted.


## Unstack

Shift Islands from Stacks in a given direction.

## Stack Mode
Mode for Stacking.

 ![](img/screen/stack/stack_modes.png)

!!! Properties
    - **Global Mode** - Collect all Similar Islands on Stacks.
    - **Selected Mode** - Collect selected Similar Islands on Stacks.
    - **Simple Mode** - Collect selected islands in the stack, with no respect for their topology.

## Stack Display Mode

### Primaries
Primaries this is islands which detected as a better instance. The position and the topology from Primaries will be translated to the Replicas. The island is defined as Primary if its position is closer to the center of coordinates, and the distortion of topology is less compared to other similar islands.

### Replicas

Replicas are islands that have the same topology but were not chosen as Primary. The position and topology of the Replicas will be changed in the process of Stacking.

### Singles

Singles this is islands that have no similar islands.

!!! Options
    ![Display](img/screen/stack/stack_display_select_sys.png)

    - **Similar** (Static) - Display all Similar Islands. Static assumes that the displaying will not change along with a mesh change.
    - **Selected** - Display Similar Islands by Selected.

    - **Stacked** ![Select](img/icons/select_bl_ico.png) - Display Stacked Islands.

    - **Primaries** ![Select](img/icons/select_bl_ico.png) - Primary Islands. Without Replicated Islands.

    - **Replicas** ![Select](img/icons/select_bl_ico.png) - Islands that can be Stacked. Without Primary Islands.

    - **Singles** ![Select](img/icons/select_bl_ico.png) - Islands that don't have Similar Islands.

    - ![](img/icons/display.png) **Display**  - Display of stacks.

    - ![](img/icons/select_bl_ico.png) **Select** - Select Stack Parts. Every operator with this icon perform a selection operation for current types.

!!! Options

    **Options for Stacked Islands**

    ![Display Stacked](img/screen/stack/stack_display_stacked_options.png)

    - **Stacked Color** - Color for displaying Stacked Islands.
    - **Only UV Area** - Display Stacks only in the UV area.

---

## Copy / Paste System

 - **Copy** - Copy parameters of selected Islands/Faces and save them.

 - **Paste** - Paste the parameters saved earlier to selected Islands/Faces.

[Here is full information](operators/stack_copy_paste.md) about Copy / Paste System.

---

## Manual Stack

!!! Panel
    ![Panel](img/screen/stack/stack_manual_stack.png)


### Area Matching ![Area Matching](img/icons/a.png)

Set strict requirements for Islands Area Matching when Stacking. Disable this option if the Islands have a slightly different Area.


### Move Only ![Move Only](img/icons/m.png)

Don't fit Islands. Just move to the same position.

### Add ![Add](img/icons/plus.png)

Add new Stack.

### Delete ![Delete](img/icons/minus.png)

Delete selected Stack.

### Add Islands ![Add Islands](img/icons/download.png)

Append selected Islands to the active Stack.

### Select Islands ![Add Islands](img/icons/select_bl_ico.png)

Select Islands in the Stack

### Analyze Stack ![Analyse Stack](img/icons/analyse.png)

Analyze Islands Similarities in the Stack. You can find details in the Zen UV Manual Stack Analyze document in the Text Editor.

### Remove All ![Remove All](img/icons/trash.png)

Remove all Manual Stacks from selected Objects.

### Stack

Collect Islands on Manual Stacks.

### Unstack

Shift Islands from Manual Stacks in a given direction.

### Stack Mode
Mode for Stacking.

!!! Options

    - **Global Mode** - Collect all Similar Islands on Stacks.
    - **Selected Mode** - Collect selected Similar Islands on Stacks.

### Display Manual Stacks

Display Manual Stacks (Static)
