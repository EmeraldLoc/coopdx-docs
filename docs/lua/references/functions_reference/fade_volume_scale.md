
## [fade_volume_scale](#fade_volume_scale)

### Description
Fades the volume of `player` to `targetScale` (0-127) over `fadeDuration`

### Lua Example
`fade_volume_scale(player, targetScale, fadeDuration)`

### Parameters
| Field | Type |
| ----- | ---- |
| player | `integer` |
| targetScale | `integer` |
| fadeDuration | `integer` |

### Returns
- None

### C Prototype
`void fade_volume_scale(u8 player, u8 targetScale, u16 fadeDuration);`
