
## [get_behavior_name_from_id](#get_behavior_name_from_id)

### Description
Gets the behavior name from the provided `id` (bhvMyGreatMODCustom004)

### Lua Example
`local stringValue = get_behavior_name_from_id(id)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- `string`

### C Prototype
`const char* get_behavior_name_from_id(enum BehaviorId id);`
