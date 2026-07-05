
## [hud_render_power_meter_interpolated](#hud_render_power_meter_interpolated)

### Description
Renders an interpolated power meter on the HUD

### Lua Example
`hud_render_power_meter_interpolated(health, prevX, prevY, prevWidth, prevHeight, x, y, width, height)`

### Parameters
| Field | Type |
| ----- | ---- |
| health | `integer` |
| prevX | `number` |
| prevY | `number` |
| prevWidth | `number` |
| prevHeight | `number` |
| x | `number` |
| y | `number` |
| width | `number` |
| height | `number` |

### Returns
- None

### C Prototype
`void hud_render_power_meter_interpolated(s32 health, f32 prevX, f32 prevY, f32 prevWidth, f32 prevHeight, f32 x, f32 y, f32 width, f32 height);`
