
## [get_id_from_vanilla_behavior](#get_id_from_vanilla_behavior)

### Description
Gets the behavior ID of the provided `behavior` if it's a vanilla behavior, `id_bhv_max_count` otherwise

### Lua Example
`local enumValue = get_id_from_vanilla_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- [enum BehaviorId](constants.md#enum-BehaviorId)

### C Prototype
`enum BehaviorId get_id_from_vanilla_behavior(const BehaviorScript* behavior);`
