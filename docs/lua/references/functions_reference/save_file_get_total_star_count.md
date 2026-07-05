
## [save_file_get_total_star_count](#save_file_get_total_star_count)

### Description
Calculates the total number of stars collected across multiple courses within a specified range.
Useful for determining the overall progress toward game completion

### Lua Example
`local integerValue = save_file_get_total_star_count(fileIndex, minCourse, maxCourse)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| minCourse | `integer` |
| maxCourse | `integer` |

### Returns
- `integer`

### C Prototype
`s32 save_file_get_total_star_count(s32 fileIndex, s32 minCourse, s32 maxCourse);`
