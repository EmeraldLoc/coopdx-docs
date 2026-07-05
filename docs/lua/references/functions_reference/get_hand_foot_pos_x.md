
## [get_hand_foot_pos_x](#get_hand_foot_pos_x)

### Description
Gets the X coordinate of Mario's hand (0-1) or foot (2-3)
but it is important to note that the positions are not updated off-screen

### Lua Example
`local numberValue = get_hand_foot_pos_x(m, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| index | `integer` |

### Returns
- `number`

### C Prototype
`f32 get_hand_foot_pos_x(struct MarioState* m, u8 index);`
