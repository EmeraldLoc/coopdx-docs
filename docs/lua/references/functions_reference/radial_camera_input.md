
## [radial_camera_input](#radial_camera_input)

### Description
Handles radial camera movement based on player input.
Updates the camera's position or orientation accordingly

### Lua Example
`local integerValue = radial_camera_input(c, unused)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| unused | `number` |

### Returns
- `integer`

### C Prototype
`s32 radial_camera_input(struct Camera *c, UNUSED f32 unused);`
