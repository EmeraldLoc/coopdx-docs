
## [mod_fs_delete](#mod_fs_delete)

### Description
Removes the provided `modFs` from persistent storage and deletes its object. Returns true on success

### Lua Example
`local booleanValue = mod_fs_delete(modFs)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_delete(struct ModFs *modFs);`
