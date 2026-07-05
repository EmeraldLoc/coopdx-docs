
## [sequence_player_set_tempo_acc](#sequence_player_set_tempo_acc)

### Description
Sets the `tempoAcc` (tempo accumulation) of `player`. Resets when another sequence is played

### Lua Example
`sequence_player_set_tempo_acc(player, tempoAcc)`

### Parameters
| Field | Type |
| ----- | ---- |
| player | `integer` |
| tempoAcc | `integer` |

### Returns
- None

### C Prototype
`void sequence_player_set_tempo_acc(u8 player, u16 tempoAcc);`
