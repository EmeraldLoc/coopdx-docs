
## [set_character_animation](#set_character_animation)

### Description
Sets the character-specific animation at its default rate (no acceleration)

### Lua Example
`local integerValue = set_character_animation(m, targetAnimID)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| targetAnimID | [enum CharacterAnimID](constants.md#enum-CharacterAnimID) |

### Returns
- `integer`

### C Prototype
`s16 set_character_animation(struct MarioState *m, enum CharacterAnimID targetAnimID);`
