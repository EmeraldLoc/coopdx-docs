
## [mod_fs_exists](#mod_fs_exists)

### Description
Checks the existence of a modfs at path `modPath` or for the active mod if not provided. Checking for the existence of a private modfs will return false, even if it exists

### Lua Example
`local booleanValue = mod_fs_exists(modPath)`

### Parameters
| Field | Type |
| ----- | ---- |
| modPath | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_fs_exists(OPTIONAL const char *modPath);`
