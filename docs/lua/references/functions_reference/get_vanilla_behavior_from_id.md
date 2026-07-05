
## [get_vanilla_behavior_from_id](#get_vanilla_behavior_from_id)

### Description
Gets the behavior script corresponding to the provided `id` if it's a vanilla behavior, `nil` otherwise

### Lua Example
`local pointerValue = get_vanilla_behavior_from_id(id)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- `Pointer` <`BehaviorScript`>

### C Prototype
`const BehaviorScript* get_vanilla_behavior_from_id(enum BehaviorId id);`
