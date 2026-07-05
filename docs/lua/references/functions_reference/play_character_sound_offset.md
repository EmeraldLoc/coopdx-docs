
## [play_character_sound_offset](#play_character_sound_offset)

### Description
Plays a character-specific sound with an additional `offset`, allowing variations or delays in the sound effect. Uses Mario's current state (`m`).
Useful for adding dynamic sound effects or syncing sounds to specific animations or events

### Lua Example
`play_character_sound_offset(m, characterSound, offset)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| characterSound | [enum CharacterSound](constants.md#enum-CharacterSound) |
| offset | `integer` |

### Returns
- None

### C Prototype
`void play_character_sound_offset(struct MarioState* m, enum CharacterSound characterSound, u32 offset);`
