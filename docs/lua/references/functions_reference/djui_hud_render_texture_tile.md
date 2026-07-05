
## [djui_hud_render_texture_tile](#djui_hud_render_texture_tile)

### Description
Renders a DJUI HUD texture tile onto the screen

### Lua Example
`djui_hud_render_texture_tile(texInfo, x, y, scaleW, scaleH, tileX, tileY, tileW, tileH)`

### Parameters
| Field | Type |
| ----- | ---- |
| texInfo | [TextureInfo](structs.md#TextureInfo) |
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
`void djui_hud_render_texture_tile(struct TextureInfo* texInfo, f32 x, f32 y, f32 scaleW, f32 scaleH, u32 tileX, u32 tileY, u32 tileW, u32 tileH);`
