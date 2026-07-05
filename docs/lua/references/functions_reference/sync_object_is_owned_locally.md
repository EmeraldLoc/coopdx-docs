
## [sync_object_is_owned_locally](#sync_object_is_owned_locally)

### Description
Checks if a sync object is owned locally using a `syncId`

### Lua Example
`local booleanValue = sync_object_is_owned_locally(syncId)`

### Parameters
| Field | Type |
| ----- | ---- |
| syncId | `integer` |

### Returns
- `boolean`

### C Prototype
`bool sync_object_is_owned_locally(u32 syncId);`
