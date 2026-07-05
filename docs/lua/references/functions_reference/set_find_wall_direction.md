
## [set_find_wall_direction](#set_find_wall_direction)

### Description
Sets whether collision finding functions should check wall directions.

### Lua Example
`set_find_wall_direction(dir, active, airborne)`

### Parameters
| Field | Type |
| ----- | ---- |
| dir | [Vec3f](structs.md#Vec3f) |
| active | `boolean` |
| airborne | `boolean` |

### Returns
- None

### C Prototype
`void set_find_wall_direction(Vec3f dir, bool active, bool airborne);`
