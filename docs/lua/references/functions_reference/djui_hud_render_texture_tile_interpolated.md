
## [djui_hud_render_texture_tile_interpolated](#djui_hud_render_texture_tile_interpolated)

### Description
Renders an interpolated DJUI HUD texture tile onto the screen

### Lua Example
`djui_hud_render_texture_tile_interpolated(texInfo, prevX, prevY, prevScaleW, prevScaleH, x, y, scaleW, scaleH, tileX, tileY, tileW, tileH)`

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
| tileX | `integer` |
| tileY | `integer` |
| tileW | `integer` |
| tileH | `integer` |

### Returns
- None

### C Prototype
`void djui_hud_render_texture_tile_interpolated(struct TextureInfo* texInfo, f32 prevX, f32 prevY, f32 prevScaleW, f32 prevScaleH, f32 x, f32 y, f32 scaleW, f32 scaleH, u32 tileX, u32 tileY, u32 tileW, u32 tileH);`
