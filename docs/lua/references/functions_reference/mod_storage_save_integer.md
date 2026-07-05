
## [mod_storage_save_integer](#mod_storage_save_integer)

### Description
Saves a `key` corresponding to an integer `value` to mod storage

### Lua Example
`local booleanValue = mod_storage_save_integer(key, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| value | `integer` |

### Returns
- `boolean`

### C Prototype
`bool mod_storage_save_integer(const char* key, lua_Integer value);`
