
## [set_mario_anim_with_accel](#set_mario_anim_with_accel)

### Description
Sets Mario's current animation to `targetAnimID` with a custom `accel` value to speed up or slow down the animation.
Useful for controlling animation timing, e.g., slow-motion or fast-forward effects

### Lua Example
`local integerValue = set_mario_anim_with_accel(m, targetAnimID, accel)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| targetAnimID | `integer` |
| accel | `integer` |

### Returns
- `integer`

### C Prototype
`s16 set_mario_anim_with_accel(struct MarioState *m, s32 targetAnimID, s32 accel);`
