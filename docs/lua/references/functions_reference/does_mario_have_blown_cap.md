
## [does_mario_have_blown_cap](#does_mario_have_blown_cap)

### Description
Checks if Mario has already had a cap blown off of his head in the current level,
Returns true if a blown cap can be found for Mario, false if not.
Useful to check if a blown cap exists in the level currently.

### Lua Example
`local booleanValue = does_mario_have_blown_cap(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `boolean`

### C Prototype
`bool does_mario_have_blown_cap(struct MarioState *m);`
