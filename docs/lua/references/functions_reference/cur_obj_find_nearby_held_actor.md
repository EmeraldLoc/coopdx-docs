
## [cur_obj_find_nearby_held_actor](#cur_obj_find_nearby_held_actor)

### Description
Finds an object with specified behavior within `maxDist` that is being held by a player

### Lua Example
`local objectValue = cur_obj_find_nearby_held_actor(behavior, maxDist)`

### Parameters
| Field | Type |
| ----- | ---- |
| behavior | `Pointer` <`BehaviorScript`> |
| maxDist | `number` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *cur_obj_find_nearby_held_actor(const BehaviorScript *behavior, f32 maxDist);`
