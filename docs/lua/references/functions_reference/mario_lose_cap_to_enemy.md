
## [mario_lose_cap_to_enemy](#mario_lose_cap_to_enemy)

### Description
Makes Mario lose his normal cap to an enemy, such as Klepto or Ukiki. Updates flags so that the cap is no longer on Mario's head.
Returns true if Mario was wearing his normal cap, otherwise false.
Useful for scenarios where enemies steal Mario's cap

### Lua Example
`local integerValue = mario_lose_cap_to_enemy(m, arg)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| arg | `integer` |

### Returns
- `integer`

### C Prototype
`u32 mario_lose_cap_to_enemy(struct MarioState* m, u32 arg);`
