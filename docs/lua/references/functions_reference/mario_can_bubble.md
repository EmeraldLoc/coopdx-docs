
## [mario_can_bubble](#mario_can_bubble)

### Description
Checks whether Mario can become bubbled under certain game conditions (multiplayer bubble mechanic). Returns false if already bubbled or if not allowed by settings

### Lua Example
`local booleanValue = mario_can_bubble(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `boolean`

### C Prototype
`bool mario_can_bubble(struct MarioState* m);`
