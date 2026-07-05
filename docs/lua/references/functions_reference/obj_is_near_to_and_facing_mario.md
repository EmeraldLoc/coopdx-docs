
## [obj_is_near_to_and_facing_mario](#obj_is_near_to_and_facing_mario)

### Description
Checks if the current object is in `maxDist` to `m` and the angle difference is less than `maxAngleDiff`

### Lua Example
`local integerValue = obj_is_near_to_and_facing_mario(m, maxDist, maxAngleDiff)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| maxDist | `number` |
| maxAngleDiff | `integer` |

### Returns
- `integer`

### C Prototype
`s32 obj_is_near_to_and_facing_mario(struct MarioState* m, f32 maxDist, s16 maxAngleDiff);`
