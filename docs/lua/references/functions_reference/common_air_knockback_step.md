
## [common_air_knockback_step](#common_air_knockback_step)

### Description
A shared step update used for airborne knockback states (both forward and backward). Updates velocity, calls `perform_air_step`,
and handles wall collisions or landing transitions to appropriate ground knockback actions. Also sets animation and speed

### Lua Example
`local integerValue = common_air_knockback_step(m, landAction, hardFallAction, animation, speed)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| landAction | `integer` |
| hardFallAction | `integer` |
| animation | `integer` |
| speed | `number` |

### Returns
- `integer`

### C Prototype
`u32 common_air_knockback_step(struct MarioState *m, u32 landAction, u32 hardFallAction, s32 animation, f32 speed);`
