
## [le_add_light](#le_add_light)

### Description
Adds a lighting engine point light at `x`, `y`, `z` with color `r`, `g`, `b` and `radius` with `intensity`

### Lua Example
`local integerValue = le_add_light(x, y, z, r, g, b, radius, intensity)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |
| r | `integer` |
| g | `integer` |
| b | `integer` |
| radius | `number` |
| intensity | `number` |

### Returns
- `integer`

### C Prototype
`s16 le_add_light(f32 x, f32 y, f32 z, u8 r, u8 g, u8 b, f32 radius, f32 intensity);`
