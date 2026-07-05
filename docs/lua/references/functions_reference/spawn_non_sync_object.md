
## [spawn_non_sync_object](#spawn_non_sync_object)

### Description
Spawns a non-synchronized object at `x`, `y`, and `z` as a child object of the local Mario with his rotation.
You can change the fields of the object in `objSetupFunction`

### Lua Example
`local objectValue = spawn_non_sync_object(behaviorId, modelId, x, y, z, objSetupFunction)`

### Parameters
| Field | Type |
| ----- | ---- |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |
| modelId | [enum ModelExtendedId](constants.md#enum-ModelExtendedId) |
| x | `number` |
| y | `number` |
| z | `number` |
| objSetupFunction | `Lua Function` () |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object* spawn_non_sync_object(enum BehaviorId behaviorId, enum ModelExtendedId modelId, f32 x, f32 y, f32 z, OPTIONAL LuaFunction objSetupFunction);`
