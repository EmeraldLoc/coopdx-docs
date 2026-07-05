
## [djui_menu_get_rainbow_string_color](#djui_menu_get_rainbow_string_color)

### Description
Gets the header hex color code from a `DJUI_RAINBOW_COLOR_*` constant

### Lua Example
`local stringValue = djui_menu_get_rainbow_string_color(color)`

### Parameters
| Field | Type |
| ----- | ---- |
| color | [enum DjuiRainbowColor](constants.md#enum-DjuiRainbowColor) |

### Returns
- `string`

### C Prototype
`char* djui_menu_get_rainbow_string_color(enum DjuiRainbowColor color);`
