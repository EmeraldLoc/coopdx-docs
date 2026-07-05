
## [touch_coin_score_age](#touch_coin_score_age)

### Description
Marks the coin score for a specific course as the newest among all save files. Adjusts the age of other scores to reflect the update.
Useful for leaderboard tracking or displaying recent progress

### Lua Example
`touch_coin_score_age(fileIndex, courseIndex)`

### Parameters
| Field | Type |
| ----- | ---- |
| fileIndex | `integer` |
| courseIndex | `integer` |

### Returns
- None

### C Prototype
`void touch_coin_score_age(s32 fileIndex, s32 courseIndex);`
