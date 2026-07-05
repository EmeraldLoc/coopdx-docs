
## [update_character_anim_offset](#update_character_anim_offset)

### Description
Updates Mario's current animation offset. This adjusts Mario's position based on the calculated offset to ensure animations appear smooth and natural.
Useful for keeping Mario's animations visually aligned, particularly when transitioning between animations

### Lua Example
`update_character_anim_offset(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void update_character_anim_offset(struct MarioState* m);`
