
## [djui_hud_render_texture](#djui_hud_render_texture)

### Description
Renders a DJUI HUD texture onto the screen

### Lua Example
`djui_hud_render_texture(texInfo, x, y, scaleW, scaleH)`

### Parameters
| Field | Type |
| ----- | ---- |
| texInfo | [TextureInfo](structs.md#TextureInfo) |
| x | `number` |
| y | `number` |
| scaleW | `number` |
| scaleH | `number` |

### Returns
- None

### C Prototype
`void djui_hud_render_texture(struct TextureInfo* texInfo, f32 x, f32 y, f32 scaleW, f32 scaleH);`
