
## [play_character_sound_if_no_flag](#play_character_sound_if_no_flag)

### Description
Plays a character-specific sound only if certain flags are not set. This ensures that sounds are not repeated unnecessarily. The sound is based on `characterSound`, and the flags are checked using `flags`.
Useful for avoiding duplicate sound effects in rapid succession or conditional actions

### Lua Example
`play_character_sound_if_no_flag(m, characterSound, flags)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| characterSound | [enum CharacterSound](constants.md#enum-CharacterSound) |
| flags | `integer` |

### Returns
- None

### C Prototype
`void play_character_sound_if_no_flag(struct MarioState* m, enum CharacterSound characterSound, u32 flags);`
