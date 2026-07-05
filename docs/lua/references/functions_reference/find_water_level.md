
## [find_water_level](#find_water_level)

### Description
Finds the height of water at a given position (x, z), if the position is within a water region.
If no water is found, returns the default height of `gLevelValues.floorLowerLimit`(-11000 by default)

### Lua Example
`local numberValue = find_water_level(x, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| z | `number` |

### Returns
- `number`

### C Prototype
`f32 find_water_level(f32 x, f32 z);`
