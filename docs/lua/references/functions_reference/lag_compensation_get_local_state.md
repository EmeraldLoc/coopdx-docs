
## [lag_compensation_get_local_state](#lag_compensation_get_local_state)

### Description
Gets the local Mario's state stored in lag compensation history

### Lua Example
`local marioStateValue = lag_compensation_get_local_state(otherNp)`

### Parameters
| Field | Type |
| ----- | ---- |
| otherNp | [NetworkPlayer](structs.md#NetworkPlayer) |

### Returns
- [MarioState](structs.md#MarioState)

### C Prototype
`struct MarioState* lag_compensation_get_local_state(struct NetworkPlayer* otherNp);`
