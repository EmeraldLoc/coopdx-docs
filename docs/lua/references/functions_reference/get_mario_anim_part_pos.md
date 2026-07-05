
## [get_mario_anim_part_pos](#get_mario_anim_part_pos)

### Description
Retrieves the animated part position associated to `animPart` from the MarioState `m` and stores it into `pos`. Returns `true` on success or `false` on failure

### Lua Example
`local booleanValue = get_mario_anim_part_pos(m, animPart, pos)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animPart | `integer` |
| pos | [Vec3f](structs.md#Vec3f) |

### Returns
- `boolean`

### C Prototype
`bool get_mario_anim_part_pos(struct MarioState *m, u32 animPart, VEC_OUT Vec3f pos);`
