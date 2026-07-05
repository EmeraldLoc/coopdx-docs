
## [save_file_is_cannon_unlocked](#save_file_is_cannon_unlocked)

### Description
Checks whether the cannon in the specified course is unlocked. Returns true if the cannon is unlocked, otherwise false.
Useful for tracking course-specific progress and enabling shortcuts

### Lua Example
`local integerValue = save_file_is_cannon_unlocked(fileIndex, courseIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |

### Returns
- `integer`

### C Prototype
`s32 save_file_is_cannon_unlocked(s32 fileIndex, s32 courseIndex);`
