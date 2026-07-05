
## [set_background_music](#set_background_music)

### Description
Sets the background music to `seqArgs` on sequence player `a` with a fade in time of `fadeTimer`

### Lua Example
`set_background_music(a, seqArgs, fadeTimer)`

### Parameters
| Field | Type |
| ----- | ---- |
| a | `integer` |
| seqArgs | `integer` |
| fadeTimer | `integer` |

### Returns
- None

### C Prototype
`void set_background_music(u16 a, u16 seqArgs, s16 fadeTimer);`
