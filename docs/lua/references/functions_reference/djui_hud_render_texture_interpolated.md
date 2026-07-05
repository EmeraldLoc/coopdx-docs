
## [djui_hud_render_texture_interpolated](#djui_hud_render_texture_interpolated)

### Description
Renders an interpolated DJUI HUD texture onto the screen

### Lua Example
`djui_hud_render_texture_interpolated(texInfo, prevX, prevY, prevScaleW, prevScaleH, x, y, scaleW, scaleH)`

### Parameters
| Field | Type |
| ----- | ---- |
| texInfo | [TextureInfo](structs.md#TextureInfo) |
| prevX | `number` |
| prevY | `number` |
| prevScaleW | `number` |
| prevScaleH | `number` |
| x | `number` |
| y | `number` |
| scaleW | `number` |
| scaleH | `number` |

### Returns
- None

### C Prototype
`void djui_hud_render_texture_interpolated(struct TextureInfo* texInfo, f32 prevX, f32 prevY, f32 prevScaleW, f32 prevScaleH, f32 x, f32 y, f32 scaleW, f32 scaleH);`
