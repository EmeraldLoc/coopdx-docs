
## [mod_fs_reload](#mod_fs_reload)

### Description
Reloads the modfs object at path `modPath`. This function will return nil for a private modfs, even if it exists

### Lua Example
`local modFsValue = mod_fs_reload(modPath)`

### Parameters
| Field | Type |
| ----- | ---- |
| modPath | `string` |

### Returns
- [ModFs](structs.md#ModFs)

### C Prototype
`struct ModFs *mod_fs_reload(OPTIONAL const char *modPath);`
