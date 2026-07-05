
## [set_water_plunge_action](#set_water_plunge_action)

### Description
Transitions Mario into a "water plunge" action, used when he enters water from above. Adjusts position, velocity, and camera mode

### Lua Example
`local integerValue = set_water_plunge_action(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 set_water_plunge_action(struct MarioState *m);`
