
## [mario_stop_riding_and_holding](#mario_stop_riding_and_holding)

### Description
Causes Mario to stop riding any object (like a shell or Hoot) and also drop any held object.
Resets related states to ensure Mario is no longer attached to or holding anything.
Useful when changing Mario's state after certain actions, transitions, or to prevent exploits

### Lua Example
`mario_stop_riding_and_holding(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void mario_stop_riding_and_holding(struct MarioState *m);`
