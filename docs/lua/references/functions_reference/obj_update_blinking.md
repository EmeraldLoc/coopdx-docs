
## [obj_update_blinking](#obj_update_blinking)

### Description
Update the current object's blinking through `oAnimState`

### Lua Example
`local blinkTimer = obj_update_blinking(blinkTimer, baseCycleLength, cycleLengthRange, blinkLength)`

### Parameters
| Field | Type |
| ----- | ---- |
| blinkTimer | `integer` |
| baseCycleLength | `integer` |
| cycleLengthRange | `integer` |
| blinkLength | `integer` |

### Returns
- `integer`

### C Prototype
`void obj_update_blinking(INOUT s32 *blinkTimer, s16 baseCycleLength, s16 cycleLengthRange, s16 blinkLength);`
