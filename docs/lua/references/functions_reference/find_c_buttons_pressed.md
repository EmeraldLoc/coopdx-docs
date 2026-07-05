
## [find_c_buttons_pressed](#find_c_buttons_pressed)

### Description
Determines which C-buttons are currently pressed by the player.
Returns a bitmask indicating the active buttons for camera control

### Lua Example
`local integerValue = find_c_buttons_pressed(currentState, buttonsPressed, buttonsDown)`

### Parameters
| Field | Type |
| ----- | ---- |
| currentState | `integer` |
| buttonsPressed | `integer` |
| buttonsDown | `integer` |

### Returns
- `integer`

### C Prototype
`s32 find_c_buttons_pressed(u16 currentState, u16 buttonsPressed, u16 buttonsDown);`
