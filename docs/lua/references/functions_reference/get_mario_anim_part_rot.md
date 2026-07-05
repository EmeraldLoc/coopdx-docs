
## [get_mario_anim_part_rot](#get_mario_anim_part_rot)

### Description
Retrieves the animated part rotation associated to `animPart` from the MarioState `m` and stores it into `rot`. Returns `true` on success or `false` on failure

### Lua Example
`local booleanValue = get_mario_anim_part_rot(m, animPart, rot)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animPart | `integer` |
| rot | [Vec3s](structs.md#Vec3s) |

### Returns
- `boolean`

### C Prototype
`bool get_mario_anim_part_rot(struct MarioState *m, u32 animPart, VEC_OUT Vec3s rot);`
