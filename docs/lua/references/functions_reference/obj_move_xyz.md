
## [obj_move_xyz](#obj_move_xyz)

### Description
Moves the object in the direction of `dx`, `dy`, and `dz`

### Lua Example
`obj_move_xyz(o, dx, dy, dz)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| dx | `number` |
| dy | `number` |
| dz | `number` |

### Returns
- None

### C Prototype
`void obj_move_xyz(struct Object *o, f32 dx, f32 dy, f32 dz);`
