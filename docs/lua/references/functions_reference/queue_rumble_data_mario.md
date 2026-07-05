
## [queue_rumble_data_mario](#queue_rumble_data_mario)

### Description
Queues rumble data with `time` and `level` only if `m` is the local Mario

### Lua Example
`queue_rumble_data_mario(m, time, level)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| time | `integer` |
| level | `integer` |

### Returns
- None

### C Prototype
`void queue_rumble_data_mario(struct MarioState* m, s16 time, s16 level);`
