
## [transition_submerged_to_walking](#transition_submerged_to_walking)

### Description
Transitions Mario from being underwater to a walking state. Resets camera to the default mode and can handle object-holding states.
Useful for restoring standard ground movement when emerging from water

### Lua Example
`local integerValue = transition_submerged_to_walking(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 transition_submerged_to_walking(struct MarioState *m);`
