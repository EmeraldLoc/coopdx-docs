
## [save_file_get_course_coin_score](#save_file_get_course_coin_score)

### Description
Returns the highest coin score for a specified course in the save file. Performs checks to ensure the coin score is valid.
Useful for tracking player achievements and high scores

### Lua Example
`local integerValue = save_file_get_course_coin_score(fileIndex, courseIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |

### Returns
- `integer`

### C Prototype
`s32 save_file_get_course_coin_score(s32 fileIndex, s32 courseIndex);`
