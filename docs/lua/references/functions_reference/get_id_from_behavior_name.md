
## [get_id_from_behavior_name](#get_id_from_behavior_name)

### Description
Gets the behavior ID corresponding to the provided `name`

### Lua Example
`local enumValue = get_id_from_behavior_name(name)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |

### Returns
- [enum BehaviorId](constants.md#enum-BehaviorId)

### C Prototype
`enum BehaviorId get_id_from_behavior_name(const char* name);`
