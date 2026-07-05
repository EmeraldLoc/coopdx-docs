
## [check_fall_damage](#check_fall_damage)

### Description
Evaluates whether Mario should take fall damage based on the height difference between his peak and current position.
If the fall is large enough and does not occur over burning surfaces or while twirling, Mario may get hurt or enter
a hard fall action. If the fall is significant but not extreme, minimal damage and a squish effect may be applied.
Useful for determining if Mario's fall warrants a health penalty or a special landing action

### Lua Example
`local integerValue = check_fall_damage(m, hardFallAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| hardFallAction | `integer` |

### Returns
- `integer`

### C Prototype
`s32 check_fall_damage(struct MarioState *m, u32 hardFallAction);`
