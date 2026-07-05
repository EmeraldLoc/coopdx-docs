
## [find_ceil](#find_ceil)

### Description
Finds the height of the highest ceiling above a given position (x, y, z) and return the corresponding ceil surface.
If no ceiling is found, returns the default height limit of `gLevelValues.cellHeightLimit`(20000 by default)

### Lua Example
`local numberValue, pceil = find_ceil(posX, posY, posZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| posX | `number` |
| posY | `number` |
| posZ | `number` |

### Returns
- `number`
- [Surface](structs.md#Surface)

### C Prototype
`f32 find_ceil(f32 posX, f32 posY, f32 posZ, RET struct Surface **pceil);`
