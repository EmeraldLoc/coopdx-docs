
## [mod_storage_load_integer](#mod_storage_load_integer)

### Description
Loads an integer `value` from a `key` in mod storage. If the `key` is not found, returns `defaultValue` or `0`

### Lua Example
`local integerValue = mod_storage_load_integer(key, defaultValue)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| defaultValue | `integer` |

### Returns
- `integer`

### C Prototype
`lua_Integer mod_storage_load_integer(const char* key, OPTIONAL lua_Integer defaultValue);`
