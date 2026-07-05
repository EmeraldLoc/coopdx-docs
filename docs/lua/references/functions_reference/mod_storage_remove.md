
## [mod_storage_remove](#mod_storage_remove)

### Description
Removes a `key` from mod storage

### Lua Example
`local booleanValue = mod_storage_remove(key)`

### Parameters
| Field | Type |
| ----- | ---- |
| key | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_storage_remove(const char* key);`
