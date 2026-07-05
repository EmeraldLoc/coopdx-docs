
## [return_mario_anim_y_translation](#return_mario_anim_y_translation)

### Description
Determines the vertical translation from Mario's animation (how much the animation moves Mario up or down). Returns the y-component of the animation's translation.
Useful for adjusting Mario's vertical position based on an ongoing animation (e.g., a bounce or jump)

### Lua Example
`local integerValue = return_mario_anim_y_translation(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s16 return_mario_anim_y_translation(struct MarioState *m);`
