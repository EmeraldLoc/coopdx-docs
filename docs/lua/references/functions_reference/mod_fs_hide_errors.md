
## [mod_fs_hide_errors](#mod_fs_hide_errors)

### Description
Hides script errors raised by `mod_fs` functions. Errors messages are still generated and can be retrieved with `mod_fs_get_last_error()`

### Lua Example
`mod_fs_hide_errors(hide)`

### Parameters
| Field | Type |
| ----- | ---- |
| hide | `boolean` |

### Returns
- None

### C Prototype
`void mod_fs_hide_errors(bool hide);`
