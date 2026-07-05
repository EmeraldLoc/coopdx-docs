
## [offset_yaw_outward_radial](#offset_yaw_outward_radial)

### Description
Calculates an outward radial offset based on the camera's yaw angle.
Returns the offset yaw, used for positioning or alignment

### Lua Example
`local integerValue = offset_yaw_outward_radial(c, areaYaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| areaYaw | `integer` |

### Returns
- `integer`

### C Prototype
`s32 offset_yaw_outward_radial(struct Camera *c, s16 areaYaw);`
