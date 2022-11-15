# Version 3.1.0.4

## Fixes

- Error when adding **UV Maps** more than 8.
- Error in **Zen Unwrap** when working with low-polygonal models (polycount < 6).
- Error in **Sort Finished** operator if there are no **Finished** islands.
- Incorrect behavior in **Stack System** - **Selected Mode** in the context of **UV Editor** - **Sync UV** - **Off**. Stacking was performed like in **Global Mode**.
- Error in the system of receiving islands when hidden islands were not ignored.
- Error in the **Excluded** system when islands tagged as **Excluded** hide in **UV Editor**.
- Error **Transform System** in **Pivot - Individual Origins**. The transformation was performed in **Pivot - Median Point** mode.

## Added

- Links to documentation for the operator **Select by UV Area** and **Excluded System**.