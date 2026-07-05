
## [queue_rumble_data_object](#queue_rumble_data_object)

### Description
Queues rumble data for object with `time` and `level`, factoring in its distance from Mario

### Lua Example
`queue_rumble_data_object(object, time, level)`

### Parameters
| Field | Type |
| ----- | ---- |
| object | [Object](structs.md#Object) |
| time | `integer` |
| level | `integer` |

### Returns
- None

### C Prototype
`void queue_rumble_data_object(struct Object* object, s16 time, s16 level);`
