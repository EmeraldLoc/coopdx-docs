
## [common_landing_action](#common_landing_action)

### Description
Applies movement upon landing from a jump or fall. Adjusts velocity based on slope or friction, checks for transitions like sliding or hitting a wall, handles small dust particles if moving fast

### Lua Example
`local integerValue = common_landing_action(m, animation, airAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation | `integer` |
| airAction | `integer` |

### Returns
- `integer`

### C Prototype
`u32 common_landing_action(struct MarioState *m, s16 animation, u32 airAction);`
