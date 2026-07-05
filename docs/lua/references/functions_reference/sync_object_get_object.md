
## [sync_object_get_object](#sync_object_get_object)

### Description
Retrieves an object from a sync ID

### Lua Example
`local objectValue = sync_object_get_object(syncId)`

### Parameters
| Field | Type |
| ----- | ---- |
| syncId | `integer` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object* sync_object_get_object(u32 syncId);`
