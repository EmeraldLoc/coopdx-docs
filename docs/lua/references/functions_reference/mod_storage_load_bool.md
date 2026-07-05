
## [mod_storage_load_bool](#mod_storage_load_bool)

### Description
Loads a bool `value` from a `key` in mod storage. If the `key` is not found, returns `defaultValue` or `false`

### Lua Example
`local booleanValue = mod_storage_load_bool(key, defaultValue)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| defaultValue | `boolean` |

### Returns
- `boolean`

### C Prototype
`bool mod_storage_load_bool(const char* key, OPTIONAL bool defaultValue);`
