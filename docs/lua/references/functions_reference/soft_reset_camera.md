
## [soft_reset_camera](#soft_reset_camera)

### Description
Resets the camera's state while retaining some settings, such as position or mode.
This is often used when soft-resetting gameplay without reinitialization

### Lua Example
`soft_reset_camera(c)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |

### Returns
- None

### C Prototype
`void soft_reset_camera(struct Camera* c);`
