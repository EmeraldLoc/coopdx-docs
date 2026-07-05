
## [cur_obj_wait_then_blink](#cur_obj_wait_then_blink)

### Description
Makes the current object blink after a delay and returns `TRUE` when blinking is complete

### Lua Example
`local integerValue = cur_obj_wait_then_blink(timeUntilBlinking, numBlinks)`

### Parameters
| Field | Type |
| ----- | ---- |
| timeUntilBlinking | `integer` |
| numBlinks | `integer` |

### Returns
- `integer`

### C Prototype
`s32 cur_obj_wait_then_blink(s32 timeUntilBlinking, s32 numBlinks);`
