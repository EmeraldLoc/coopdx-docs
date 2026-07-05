
## [collision_find_ceil](#collision_find_ceil)

### Description
Finds a potential ceiling at the given `x`, `y`, and `z` values

### Lua Example
`local surfaceValue = collision_find_ceil(x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface* collision_find_ceil(f32 x, f32 y, f32 z);`
