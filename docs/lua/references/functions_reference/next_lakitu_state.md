
## [next_lakitu_state](#next_lakitu_state)

### Description
Transitions the camera to the next Lakitu state, updating position and focus.
This function handles smooth transitions between different gameplay scenarios

### Lua Example
`local integerValue = next_lakitu_state(newPos, newFoc, curPos, curFoc, oldPos, oldFoc, yaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| newPos | [Vec3f](structs.md#Vec3f) |
| newFoc | [Vec3f](structs.md#Vec3f) |
| curPos | [Vec3f](structs.md#Vec3f) |
| curFoc | [Vec3f](structs.md#Vec3f) |
| oldPos | [Vec3f](structs.md#Vec3f) |
| oldFoc | [Vec3f](structs.md#Vec3f) |
| yaw | `integer` |

### Returns
- `integer`

### C Prototype
`s16 next_lakitu_state(VEC_OUT Vec3f newPos, VEC_OUT Vec3f newFoc, Vec3f curPos, Vec3f curFoc, Vec3f oldPos, Vec3f oldFoc, s16 yaw);`
