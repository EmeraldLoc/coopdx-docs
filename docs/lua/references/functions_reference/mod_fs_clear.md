
## [mod_fs_clear](#mod_fs_clear)

### Description
Deletes all files of the provided `modFs`. Returns true on success

### Lua Example
`local booleanValue = mod_fs_clear(modFs)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_clear(struct ModFs *modFs);`
