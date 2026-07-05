
## [find_ceil_height](#find_ceil_height)

### Description
Finds the height of the highest ceiling above a given position (x, y, z).
If no ceiling is found, returns the default height limit of `gLevelValues.cellHeightLimit`(20000 by default)

### Lua Example
`local numberValue = find_ceil_height(x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- `number`

### C Prototype
`f32 find_ceil_height(f32 x, f32 y, f32 z);`
