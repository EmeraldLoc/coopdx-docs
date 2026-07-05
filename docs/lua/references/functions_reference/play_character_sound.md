
## [play_character_sound](#play_character_sound)

### Description
Plays a character-specific sound based on the given `characterSound` value. The sound is tied to Mario's current state (`m`).
Useful for triggering sound effects for actions like jumping or interacting with the environment

### Lua Example
`play_character_sound(m, characterSound)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| characterSound | [enum CharacterSound](constants.md#enum-CharacterSound) |

### Returns
- None

### C Prototype
`void play_character_sound(struct MarioState* m, enum CharacterSound characterSound);`
