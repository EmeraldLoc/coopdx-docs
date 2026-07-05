
## [find_floor](#find_floor)

### Description
Finds the height of the highest floor below a given position (x, y, z) and return the corresponding floor surface.
If no floor is found, returns the default floor height of `gLevelValues.floorLowerLimit`(-11000 by default)

### Lua Example
`local numberValue, pfloor = find_floor(xPos, yPos, zPos)`

### Parameters
| Field | Type |
| ----- | ---- |
| xPos | `number` |
| yPos | `number` |
| zPos | `number` |

### Returns
- `number`
- [Surface](structs.md#Surface)

### C Prototype
`f32 find_floor(f32 xPos, f32 yPos, f32 zPos, RET struct Surface **pfloor);`
