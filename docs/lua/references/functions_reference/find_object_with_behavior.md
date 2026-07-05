
## [find_object_with_behavior](#find_object_with_behavior)

### Description
Finds any object with the specified behavior

### Lua Example
`local objectValue = find_object_with_behavior(behavior)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *find_object_with_behavior(const BehaviorScript *behavior);`
