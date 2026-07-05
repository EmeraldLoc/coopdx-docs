
## [passes_pvp_interaction_checks](#passes_pvp_interaction_checks)

### Description
Checks if the necessary conditions are met for one player to successfully attack another player in a PvP scenario.
Considers factors like invincibility, action states, and whether the attack is valid.
Useful for multiplayer where players can harm each other

### Lua Example
`local integerValue = passes_pvp_interaction_checks(attacker, victim)`

### Parameters
| Field | Type |
| ----- | ---- |
| attacker | [MarioState](structs.md#MarioState) |
| victim | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`u8 passes_pvp_interaction_checks(struct MarioState* attacker, struct MarioState* victim);`
