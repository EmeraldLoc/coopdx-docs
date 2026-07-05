
## [common_ground_knockback_action](#common_ground_knockback_action)

### Description
Handles knockback on the ground (getting hit while on the ground) with shared logic for multiple knockback states. Applies deceleration or minimal momentum, chooses appropriate landing action if Mario leaves the ground, and handles death transitions if Mario's health is depleted

### Lua Example
`local integerValue = common_ground_knockback_action(m, animation, arg2, arg3, arg4)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| animation | `integer` |
| arg2 | `integer` |
| arg3 | `integer` |
| arg4 | `integer` |

### Returns
- `integer`

### C Prototype
`s32 common_ground_knockback_action(struct MarioState *m, s32 animation, s32 arg2, s32 arg3, s32 arg4);`
