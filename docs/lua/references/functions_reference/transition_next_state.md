
## [transition_next_state](#transition_next_state)

### Description
Transitions the camera to the next state over a specified number of frames.
This is typically used for cutscenes or scripted sequences

### Lua Example
`transition_next_state(c, frames)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| frames | `integer` |

### Returns
- None

### C Prototype
`void transition_next_state(UNUSED struct Camera *c, s16 frames);`
