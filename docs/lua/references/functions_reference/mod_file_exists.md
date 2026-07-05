
## [mod_file_exists](#mod_file_exists)

### Description
Checks if a file exists inside of a mod

### Lua Example
`local booleanValue = mod_file_exists(filename)`

### Parameters
| Field | Type |
| ----- | ---- |
| filename | `string` |

### Returns
- `boolean`

### C Prototype
`bool mod_file_exists(const char* filename);`
