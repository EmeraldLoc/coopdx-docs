
## [find_mario_anim_flags_and_translation](#find_mario_anim_flags_and_translation)

### Description
Retrieves the current animation flags and calculates the translation for Mario's animation, rotating it into the global coordinate system based on `yaw`.
Useful for determining positional offsets from animations (e.g., stepping forward in a walk animation) and applying them to Mario's position

### Lua Example
`local integerValue = find_mario_anim_flags_and_translation(o, yaw, translation)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| yaw | `integer` |
| translation | [Vec3s](structs.md#Vec3s) |

### Returns
- `integer`

### C Prototype
`s16 find_mario_anim_flags_and_translation(struct Object *o, s32 yaw, VEC_OUT Vec3s translation);`
