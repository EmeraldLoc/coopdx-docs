
## [mod_storage_load](#mod_storage_load)

### Description
Loads a string `value` from a `key` in mod storage. If the `key` is not found, returns `defaultValue` or `nil`

### Lua Example
`local stringValue = mod_storage_load(key, defaultValue)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |
| defaultValue | `string` |

### Returns
- `string`

### C Prototype
`const char *mod_storage_load(const char* key, OPTIONAL const char* defaultValue);`
