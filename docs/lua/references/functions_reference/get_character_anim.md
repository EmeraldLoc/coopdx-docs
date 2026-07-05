
## [get_character_anim](#get_character_anim)

### Description
Gets the animation ID to use for a specific character and animation combination. The ID is based on `characterAnim` and the character currently controlled by Mario (`m`).
Useful for determining which animation to play for actions like walking, jumping, or idle states

### Lua Example
`local integerValue = get_character_anim(m, characterAnim)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| characterAnim | [enum CharacterAnimID](constants.md#enum-CharacterAnimID) |

### Returns
- `integer`

### C Prototype
`s32 get_character_anim(struct MarioState* m, enum CharacterAnimID characterAnim);`
