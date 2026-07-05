
## [get_character_anim_offset](#get_character_anim_offset)

### Description
Calculates the animation offset for Mario's current animation. The offset is determined by the type of animation being played (e.g., hand, feet, or torso movement).
Useful for smoothly syncing Mario's model height or positional adjustments during animations

### Lua Example
`local numberValue = get_character_anim_offset(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `number`

### C Prototype
`f32 get_character_anim_offset(struct MarioState* m);`
