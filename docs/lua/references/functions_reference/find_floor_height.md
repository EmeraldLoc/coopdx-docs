
## [find_floor_height](#find_floor_height)

### Description
Finds the height of the highest floor below a given position (x, y, z).
If no floor is found, returns the default floor height of `gLevelValues.floorLowerLimit`(-11000 by default)

### Lua Example
`local numberValue = find_floor_height(x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- `number`

### C Prototype
`f32 find_floor_height(f32 x, f32 y, f32 z);`
