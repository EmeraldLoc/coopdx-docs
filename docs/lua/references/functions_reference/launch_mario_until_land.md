
## [launch_mario_until_land](#launch_mario_until_land)

### Description
Launches Mario forward with a given velocity (`forwardVel`) and sets his animation. Continues moving him through the air until he lands, then changes Mario's action to `endAction`

### Lua Example
`local integerValue = launch_mario_until_land(m, endAction, animation, forwardVel)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| endAction | `integer` |
| animation | `integer` |
| forwardVel | `number` |

### Returns
- `integer`

### C Prototype
`s32 launch_mario_until_land(struct MarioState *m, s32 endAction, s32 animation, f32 forwardVel);`
