
## [get_object_list_from_behavior](#get_object_list_from_behavior)

### Description
Retrieves the object list type that a behavior script belongs to

### Lua Example
`local integerValue = get_object_list_from_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- `integer`

### C Prototype
`u32 get_object_list_from_behavior(const BehaviorScript *behavior);`
