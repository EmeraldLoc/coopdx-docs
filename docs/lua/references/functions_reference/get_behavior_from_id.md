
## [get_behavior_from_id](#get_behavior_from_id)

### Description
Gets the behavior script corresponding to the provided `id`

### Lua Example
`local pointerValue = get_behavior_from_id(id)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- `Pointer` <`BehaviorScript`>

### C Prototype
`const BehaviorScript* get_behavior_from_id(enum BehaviorId id);`
