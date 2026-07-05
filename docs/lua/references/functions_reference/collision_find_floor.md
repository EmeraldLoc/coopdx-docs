
## [collision_find_floor](#collision_find_floor)

### Description
Finds a potential floor at the given `x`, `y`, and `z` values

### Lua Example
`local surfaceValue = collision_find_floor(x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface* collision_find_floor(f32 x, f32 y, f32 z);`
