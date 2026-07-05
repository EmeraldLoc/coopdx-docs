
## [obj_turn_pitch_toward_mario](#obj_turn_pitch_toward_mario)

### Description
Turns the current object towards `m` by `turnAmount` and subtracts and adds `targetOffsetY` to the Y position, effectively cancelling any effect out

### Lua Example
`local integerValue = obj_turn_pitch_toward_mario(m, targetOffsetY, turnAmount)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| targetOffsetY | `number` |
| turnAmount | `integer` |

### Returns
- `integer`

### C Prototype
`s16 obj_turn_pitch_toward_mario(struct MarioState* m, f32 targetOffsetY, s16 turnAmount);`
