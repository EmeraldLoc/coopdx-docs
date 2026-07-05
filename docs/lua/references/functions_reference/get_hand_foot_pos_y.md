
## [get_hand_foot_pos_y](#get_hand_foot_pos_y)

### Description
Gets the Y coordinate of Mario's hand (0-1) or foot (2-3)
but It is important to note that the positions are not updated off-screen

### Lua Example
`local numberValue = get_hand_foot_pos_y(m, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| index | `integer` |

### Returns
- `number`

### C Prototype
`f32 get_hand_foot_pos_y(struct MarioState* m, u8 index);`
