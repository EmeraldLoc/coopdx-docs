
## [mod_fs_save](#mod_fs_save)

### Description
Saves the provided `modFs` to persistent storage. Returns true on success

### Lua Example
`local booleanValue = mod_fs_save(modFs)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_save(struct ModFs *modFs);`
