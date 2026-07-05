
## [sync_object_is_initialized](#sync_object_is_initialized)

### Description
Checks if a sync object is initialized using a `syncId`

### Lua Example
`local booleanValue = sync_object_is_initialized(syncId)`

### Parameters
| Field | Type |
| ----- | ---- |
| syncId | `integer` |

### Returns
- `boolean`

### C Prototype
`bool sync_object_is_initialized(u32 syncId);`
