
## [djui_hud_measure_text](#djui_hud_measure_text)

### Description
Measures the width and height of `message` in the current font

### Lua Example
`local width, height = djui_hud_measure_text(message)`

### Parameters
| Field | Type |
| ----- | ---- |
| message | `string` |

### Returns
- `number`
- `number`

### C Prototype
`void djui_hud_measure_text(const char* message, RET f32 *width, RET f32 *height);`
