
## [le_get_light_pos](#le_get_light_pos)

### Description
Outputs a lighting engine point light's position to `out`

### Lua Example
`le_get_light_pos(id, out)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | `integer` |
| out | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void le_get_light_pos(s16 id, VEC_OUT Vec3f out);`
