
## [save_file_get_course_star_count](#save_file_get_course_star_count)

### Description
Calculates the total number of stars collected in a specific course for a given save file.
Useful for determining completion status of individual levels

### Lua Example
`local integerValue = save_file_get_course_star_count(fileIndex, courseIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |

### Returns
- `integer`

### C Prototype
`s32 save_file_get_course_star_count(s32 fileIndex, s32 courseIndex);`
