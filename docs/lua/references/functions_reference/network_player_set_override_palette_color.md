
## [network_player_set_override_palette_color](#network_player_set_override_palette_color)

### Description
Sets the `part in `np`'s override color palette`

### Lua Example
`network_player_set_override_palette_color(np, part, color)`

### Parameters
| Field | Type |
| ----- | ---- |
| np | [NetworkPlayer](structs.md#NetworkPlayer) |
| part | [enum PlayerPart](constants.md#enum-PlayerPart) |
| color | [Color](structs.md#Color) |

### Returns
- None

### C Prototype
`void network_player_set_override_palette_color(struct NetworkPlayer *np, enum PlayerPart part, Color color);`
