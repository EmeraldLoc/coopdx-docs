
## [rotate_camera_around_walls](#rotate_camera_around_walls)

### Description
Rotates the camera to avoid walls or other obstructions.
Ensures clear visibility of the player or target objects

### Lua Example
`local integerValue, avoidYaw = rotate_camera_around_walls(c, cPos, avoidYaw, yawRange)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| cPos | [Vec3f](structs.md#Vec3f) |
| avoidYaw | `integer` |
| yawRange | `integer` |

### Returns
- `integer`
- `integer`

### C Prototype
`s32 rotate_camera_around_walls(struct Camera *c, Vec3f cPos, INOUT s16 *avoidYaw, s16 yawRange);`
