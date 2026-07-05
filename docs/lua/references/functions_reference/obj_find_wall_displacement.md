
## [obj_find_wall_displacement](#obj_find_wall_displacement)

### Description
Finds any wall collisions and returns what the displacement vector would be

### Lua Example
`local integerValue = obj_find_wall_displacement(dist, x, y, z, radius)`

### Parameters
| Field | Type |
| ----- | ---- |
| dist | [Vec3f](structs.md#Vec3f) |
| x | `number` |
| y | `number` |
| z | `number` |
| radius | `number` |

### Returns
- `integer`

### C Prototype
`s8 obj_find_wall_displacement(VEC_OUT Vec3f dist, f32 x, f32 y, f32 z, f32 radius);`
