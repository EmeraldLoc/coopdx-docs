
## [get_id_from_behavior](#get_id_from_behavior)

### Description
Gets the behavior ID of the provided `behavior`

### Lua Example
`local enumValue = get_id_from_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- [enum BehaviorId](constants.md#enum-BehaviorId)

### C Prototype
`enum BehaviorId get_id_from_behavior(const BehaviorScript* behavior);`
