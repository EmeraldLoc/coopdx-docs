
## [vec3f_find_ceil](#vec3f_find_ceil)

### Description
Finds the ceiling from a vec3f horizontally and a height (with 80 vertical buffer).
Returns the ceiling height and surface

### Lua Example
`local numberValue, ceil = vec3f_find_ceil(pos, height)`

### Parameters
| Field | Type |
| ----- | ---- |
| pos | [Vec3f](structs.md#Vec3f) |
| height | `number` |

### Returns
- `number`
- [Surface](structs.md#Surface)

### C Prototype
`f32 vec3f_find_ceil(Vec3f pos, f32 height, RET struct Surface **ceil);`
