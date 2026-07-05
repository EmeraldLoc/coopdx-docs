
## [level_trigger_warp](#level_trigger_warp)

### Description
Triggers a warp (WARP_OP_*) for the level. Pass in `gMarioStates[0]` for `m`

### Lua Example
`local integerValue = level_trigger_warp(m, warpOp)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| warpOp | `integer` |

### Returns
- `integer`

### C Prototype
`s16 level_trigger_warp(struct MarioState *m, s32 warpOp);`
