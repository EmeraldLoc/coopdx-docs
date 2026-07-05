
## [does_mario_have_normal_cap_on_head](#does_mario_have_normal_cap_on_head)

### Description
Checks if Mario is currently wearing his normal cap on his head.
Returns true if Mario's flag state matches that of having the normal cap equipped on his head, otherwise false.
Useful for determining Mario's cap status

### Lua Example
`local integerValue = does_mario_have_normal_cap_on_head(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`u32 does_mario_have_normal_cap_on_head(struct MarioState *m);`
