
## [anim_and_audio_for_walk](#anim_and_audio_for_walk)

### Description
Handles the animation and audio (footstep sounds) for normal walking or running.
The specific animation used (tiptoe, walk, or run) depends on Mario's current speed

### Lua Example
`anim_and_audio_for_walk(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void anim_and_audio_for_walk(struct MarioState *m);`
