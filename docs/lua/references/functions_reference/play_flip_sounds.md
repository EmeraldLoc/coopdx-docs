
## [play_flip_sounds](#play_flip_sounds)

### Description
Plays a spinning sound at specific animation frames for flips (usually side flips or certain jump flips).
If the current animation frame matches any of the specified frames, it triggers `SOUND_ACTION_SPIN`

### Lua Example
`play_flip_sounds(m, frame1, frame2, frame3)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| frame1 | `integer` |
| frame2 | `integer` |
| frame3 | `integer` |

### Returns
- None

### C Prototype
`void play_flip_sounds(struct MarioState *m, s16 frame1, s16 frame2, s16 frame3);`
