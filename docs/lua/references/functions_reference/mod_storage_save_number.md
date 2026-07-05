
## [mod_storage_save_number](#mod_storage_save_number)

### Description
Saves a `key` corresponding to a number `value` to mod storage

### Lua Example
`local booleanValue = mod_storage_save_number(key, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| value | `number` |

### Returns
- `boolean`

### C Prototype
`bool mod_storage_save_number(const char* key, lua_Number value);`
