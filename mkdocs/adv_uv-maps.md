# Advanced UV Maps

!!! Info
    We would like to inform you that the documentation available on this web page pertains exclusively to Zen UV 3. However, we would like to emphasize that [**Zen UV 4 is now available and offers a significantly improved user experience**](https://zenmastersteam.github.io/Zen-UV/latest/).

    We also remind that Zen UV 3 users can [**Upgrade Zen UV 3 to Zen UV 4 with a discount!**](https://zenmastersteam.github.io/Zen-UV/latest/zenuv3_to_zenuv4/#upgrade-zen-uv-3-to-zen-uv-4-faq)

!!! Panel
    ![Advanced UV Map](img/screen/adv_uv_map/adv_uv_map.png)

Advanced UV Maps section created to have quick access to Object Data Properties — UV Maps.

It allows to select the active, add, remove, and rename UV Maps from the list.

If more than one object is selected, you can synchronously work with UV maps of the selected objects.

---
## Clean UV Maps
Remove inactive UV Map.

!!! tip
    Hold [Zen Modifier Key](addon_prefs.md/#zen-modifier-key) (default 'Alt') to apply on all selected objects.

---
## Rename UV Maps
Rename UV Map using pattern. The pattern can be defined in the operator popup.

![](img/screen/adv_uv_map/rename_uv_maps_popup.png)

   - **Name** - The pattern.
   - **Use Default Name** - Use the native name defined in Blender.
   - **Use Numbering** - Add numbers to the end of the name.
   - **Active Only** - Rename Active UV Maps only.

!!! tip
    Hold [Zen Modifier Key](addon_prefs.md/#zen-modifier-key) (default 'Alt') to apply on all selected objects.

---
## Duplicate active UV Map ![Add Button](img/icons/plus.png)
Duplicate the active UV Map or create a new one depending on the operator's properties.
![](img/screen/adv_uv_map/duplicate_active_map.png)

!!! tip
    Hold [Zen Modifier Key](addon_prefs.md/#zen-modifier-key) (default 'Alt') to apply on all selected objects.

---
## Remove active UV Map ![Remove Button](img/icons/minus.png)
Remove active UV Map.

!!! tip
    Hold [Zen Modifier Key](addon_prefs.md/#zen-modifier-key) (default 'Alt') to apply on all selected objects.

---
## Sync UV Maps IDs ![Sync Button](img/icons/adv_uv_sync.png)
Set the same active UV Map index for all selected objects.
Alt + Click - activates automatic synchronization mode.

In automatic synchronization mode:

   ![True Sync Button](img/icons/adv_uv_sync_true.png) If the background of the button is blue, the UVs are synchronized.

   ![False Sync Button](img/icons/adv_uv_sync_false.png) If the background of the button is purple, the UVs are out of sync.

---

## Copy UV / Paste UV

Allows transferring the UV coordinates between UV Maps.

![](img/screen/adv_uv_map/uv_copy_paste.png)

**Copy UV** - Copy the UV coordinates of the selection.

**Paste UV** - Paste the UV coordinates.