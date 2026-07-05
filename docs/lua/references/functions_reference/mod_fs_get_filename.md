
## [mod_fs_get_filename](#mod_fs_get_filename)

### Description
Gets the filename at position `index` of the provided `modFs`

### Lua Example
`local stringValue = mod_fs_get_filename(modFs, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| index | `integer` |

### Returns
- `string`

### C Prototype
`const char *mod_fs_get_filename(struct ModFs *modFs, u16 index);`
