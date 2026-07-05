
## [mod_fs_get](#mod_fs_get)

### Description
Gets the modfs object at path `modPath` or the active mod one if not provided. This function will return nil for a private modfs, even if it exists

### Lua Example
`local modFsValue = mod_fs_get(modPath)`

### Parameters
| Field | Type |
| ----- | ---- |
| modPath | `string` |

### Returns
- [ModFs](structs.md#ModFs)

### C Prototype
`struct ModFs *mod_fs_get(OPTIONAL const char *modPath);`
