
## [mario_ready_to_speak](#mario_ready_to_speak)

### Description
Checks if Mario's current action allows him to speak. For Mario to be ready, his action must be in a 'stationary' or 'moving' group (or waiting for dialog), and he must not be riding a shell, invulnerable, or in first-person mode

### Lua Example
`local integerValue = mario_ready_to_speak(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 mario_ready_to_speak(struct MarioState* m);`
