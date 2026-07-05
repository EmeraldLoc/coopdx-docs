
## [anim_and_audio_for_hold_walk](#anim_and_audio_for_hold_walk)

### Description
Plays the appropriate animation and footstep sounds for walking while carrying a lighter object (like a small box).
Adjusts the animation speed dynamically based on Mario's velocity

### Lua Example
`anim_and_audio_for_hold_walk(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void anim_and_audio_for_hold_walk(struct MarioState *m);`
