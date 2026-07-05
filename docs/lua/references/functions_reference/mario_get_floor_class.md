
## [mario_get_floor_class](#mario_get_floor_class)

### Description
Retrieves the slipperiness class of Mario's current floor, ranging from not slippery to very slippery. Considers terrain types and special surfaces.
Useful for controlling friction, movement speed adjustments, and whether Mario slips or walks

### Lua Example
`local integerValue = mario_get_floor_class(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_get_floor_class(struct MarioState *m);`
