
## [update_sliding_angle](#update_sliding_angle)

### Description
Adjusts Mario's slide velocity and facing angle when on a slope.
Calculates slope direction and steepness, then modifies velocity accordingly (speed up downhill, slow uphill).
Handles facing-direction changes and maximum speed limits

### Lua Example
`update_sliding_angle(m, accel, lossFactor)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| accel | `number` |
| lossFactor | `number` |

### Returns
- None

### C Prototype
`void update_sliding_angle(struct MarioState *m, f32 accel, f32 lossFactor);`
