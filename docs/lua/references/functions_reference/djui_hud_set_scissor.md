
## [djui_hud_set_scissor](#djui_hud_set_scissor)

### Description
Sets the scissor rectangle to the specified position and size, this will cut off any subsequent DJUI graphics not within the rectangle

### Lua Example
`djui_hud_set_scissor(x, y, width, height)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| width | `number` |
| height | `number` |

### Returns
- None

### C Prototype
`void djui_hud_set_scissor(f32 x, f32 y, f32 width, f32 height);`
