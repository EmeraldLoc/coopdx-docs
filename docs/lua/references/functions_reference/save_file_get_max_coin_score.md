
## [save_file_get_max_coin_score](#save_file_get_max_coin_score)

### Description
Determines the maximum coin score for a course across all save files. Returns the score along with the file index of the save containing it.
Useful for leaderboard-style comparisons and overall progress tracking

### Lua Example
`local integerValue = save_file_get_max_coin_score(courseIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| courseIndex | `integer` |

### Returns
- `integer`

### C Prototype
`u32 save_file_get_max_coin_score(s32 courseIndex);`
