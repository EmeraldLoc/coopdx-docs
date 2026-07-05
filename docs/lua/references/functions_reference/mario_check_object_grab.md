
## [mario_check_object_grab](#mario_check_object_grab)

### Description
Checks if Mario can grab the currently encountered object (usually triggered when Mario punches or dives). If conditions are met, initiates the grabbing process.
Useful for picking up objects, throwing enemies, or grabbing special items

### Lua Example
`local integerValue = mario_check_object_grab(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`u32 mario_check_object_grab(struct MarioState *m);`
