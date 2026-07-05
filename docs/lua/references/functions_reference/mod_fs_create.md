
## [mod_fs_create](#mod_fs_create)

### Description
Creates a modfs object for the active mod if it doesn't exist. Returns the modfs object on success

### Lua Example
`local modFsValue = mod_fs_create()`

### Parameters
- None

### Returns
- [ModFs](structs.md#ModFs)

### C Prototype
`struct ModFs *mod_fs_create();`
