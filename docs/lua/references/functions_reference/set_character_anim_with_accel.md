
## [set_character_anim_with_accel](#set_character_anim_with_accel)

### Description
Sets a character-specific animation where the animation speed is adjusted by `accel`.
Useful for varying animation speeds based on context or dynamic conditions (e.g., slow-motion)

### Lua Example
`local integerValue = set_character_anim_with_accel(m, targetAnimID, accel)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| targetAnimID | [enum CharacterAnimID](constants.md#enum-CharacterAnimID) |
| accel | `integer` |

### Returns
- `integer`

### C Prototype
`s16 set_character_anim_with_accel(struct MarioState *m, enum CharacterAnimID targetAnimID, s32 accel);`
