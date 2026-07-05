
## [djui_language_get](#djui_language_get)

### Description
Gets a language `key` from a `section`

### Lua Example
`local stringValue = djui_language_get(section, key)`

### Parameters
| Field | Type |
| ----- | ---- |
| section | `string` |
| key | `string` |

### Returns
- `string`

### C Prototype
`char* djui_language_get(const char *section, const char *key);`
