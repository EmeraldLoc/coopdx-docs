
## [cur_obj_can_mario_activate_textbox](#cur_obj_can_mario_activate_textbox)

### Description
Checks whether Mario can activate the current object's textbox within a vertical and horizontal range

### Lua Example
`local integerValue = cur_obj_can_mario_activate_textbox(m, radius, height, unused)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| radius | `number` |
| height | `number` |
| unused | `integer` |

### Returns
- `integer`

### C Prototype
`s32 cur_obj_can_mario_activate_textbox(struct MarioState* m, f32 radius, f32 height, OPTIONAL UNUSED s32 unused);`
