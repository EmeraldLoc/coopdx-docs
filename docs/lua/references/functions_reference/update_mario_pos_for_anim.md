
## [update_mario_pos_for_anim](#update_mario_pos_for_anim)

### Description
Applies the translation from Mario's current animation to his world position. Considers animation flags (horizontal/vertical translation)

### Lua Example
`update_mario_pos_for_anim(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_mario_pos_for_anim(struct MarioState *m);`
