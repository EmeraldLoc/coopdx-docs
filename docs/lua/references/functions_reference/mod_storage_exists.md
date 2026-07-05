
## [mod_storage_exists](#mod_storage_exists)

### Description
Checks if a `key` is in mod storage

### Lua Example
`local booleanValue = mod_storage_exists(key)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_storage_exists(const char* key);`
