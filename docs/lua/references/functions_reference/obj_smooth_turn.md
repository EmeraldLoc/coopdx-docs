
## [obj_smooth_turn](#obj_smooth_turn)

### Description
Smoothly turns `angle` and adjust `angleVel` using parameters. Returns TRUE if `angle` reaches `targetAngle`

### Lua Example
`local integerValue, angleVel, angle = obj_smooth_turn(angleVel, angle, targetAngle, targetSpeedProportion, accel, minSpeed, maxSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| angleVel | `integer` |
| angle | `integer` |
| targetAngle | `integer` |
| targetSpeedProportion | `number` |
| accel | `integer` |
| minSpeed | `integer` |
| maxSpeed | `integer` |

### Returns
- `integer`
- `integer`
- `integer`

### C Prototype
`s32 obj_smooth_turn(INOUT s16 *angleVel, INOUT s32 *angle, s16 targetAngle, f32 targetSpeedProportion, s16 accel, s16 minSpeed, s16 maxSpeed);`
