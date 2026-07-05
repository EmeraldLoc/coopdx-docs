
## [mod_fs_set_public](#mod_fs_set_public)

### Description
Marks the provided `modFs` as public (i.e. readable by other mods). Returns true on success

### Lua Example
`local booleanValue = mod_fs_set_public(modFs, pub)`

### Parameters
| Field | Type |
| ----- | ---- |
| modFs | [ModFs](structs.md#ModFs) |
| pub | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_set_public(struct ModFs *modFs, bool pub);`
