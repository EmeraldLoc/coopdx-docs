
## [sequence_player_set_transposition](#sequence_player_set_transposition)

### Description
Sets the `transposition` (pitch) of `player`. Resets when another sequence is played

### Lua Example
`sequence_player_set_transposition(player, transposition)`

### Parameters
| Field | Type |
| ----- | ---- |
| player | `integer` |
| transposition | `integer` |

### Returns
- None

### C Prototype
`void sequence_player_set_transposition(u8 player, u16 transposition);`
