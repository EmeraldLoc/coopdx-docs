
## [set_mario_animation](#set_mario_animation)

### Description
Sets Mario's current animation to `targetAnimID` at a default acceleration (no speed change)

### Lua Example
`local integerValue = set_mario_animation(m, targetAnimID)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| targetAnimID | `integer` |

### Returns
- `integer`

### C Prototype
`s16 set_mario_animation(struct MarioState *m, s32 targetAnimID);`
