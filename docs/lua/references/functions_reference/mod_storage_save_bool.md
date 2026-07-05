
## [mod_storage_save_bool](#mod_storage_save_bool)

### Description
Saves a `key` corresponding to a bool `value` to mod storage

### Lua Example
`local booleanValue = mod_storage_save_bool(key, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| value | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_storage_save_bool(const char* key, bool value);`
