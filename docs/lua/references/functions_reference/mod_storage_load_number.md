
## [mod_storage_load_number](#mod_storage_load_number)

### Description
Loads a number `value` from a `key` in mod storage. If the `key` is not found, returns `defaultValue` or `0`

### Lua Example
`local numberValue = mod_storage_load_number(key, defaultValue)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| defaultValue | `number` |

### Returns
- `number`

### C Prototype
`lua_Number mod_storage_load_number(const char* key, OPTIONAL lua_Number defaultValue);`
