
## [save_file_set_course_coin_score](#save_file_set_course_coin_score)

### Description
Updates the coin score for a specific course in the save file. The new score is provided in the `coinScore` parameter.
Useful for manually setting achievements such as high coin counts in individual levels

### Lua Example
`save_file_set_course_coin_score(fileIndex, courseIndex, coinScore)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |
| coinScore | `integer` |

### Returns
- None

### C Prototype
`void save_file_set_course_coin_score(s32 fileIndex, s32 courseIndex, u8 coinScore);`
