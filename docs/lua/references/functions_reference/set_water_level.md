
## [set_water_level](#set_water_level)

### Description
Sets the water level in an area corresponding to `index` (0-indexed)

### Lua Example
`set_water_level(index, height, sync)`

### Parameters
| Field | Type |
| ----- | ---- |
| index | `integer` |
| height | `integer` |
| sync | `boolean` |

### Returns
- None

### C Prototype
`void set_water_level(u8 index, s16 height, bool sync);`
