
## [common_anchor_mario_behavior](#common_anchor_mario_behavior)

### Description
Common behavior for an object when grabbing Mario. Used by King Bob-omb and Chuckya anchor objects. When Mario is thrown, sets `forwardVel`, `upwardsVel` and `interactStatusFlags` to him

### Lua Example
`common_anchor_mario_behavior(forwardVel, upwardsVel, interactStatusFlags)`

### Parameters
| Field | Type |
| ----- | ---- |
| forwardVel | `number` |
| upwardsVel | `number` |
| interactStatusFlags | `integer` |

### Returns
- None

### C Prototype
`void common_anchor_mario_behavior(f32 forwardVel, f32 upwardsVel, s32 interactStatusFlags);`
