
## [mario_update_quicksand](#mario_update_quicksand)

### Description
Updates Mario's state in quicksand, sinks him at `sinkingSpeed` if he's in non instant quicksand

### Lua Example
`local integerValue = mario_update_quicksand(m, sinkingSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| sinkingSpeed | `number` |

### Returns
- `integer`

### C Prototype
`u32 mario_update_quicksand(struct MarioState *m, f32 sinkingSpeed);`
