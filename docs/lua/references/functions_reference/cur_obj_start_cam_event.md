
## [cur_obj_start_cam_event](#cur_obj_start_cam_event)

### Description
Starts a camera event and makes the current object the secondary camera focus

### Lua Example
`cur_obj_start_cam_event(obj, cameraEvent)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| cameraEvent | `integer` |

### Returns
- None

### C Prototype
`void cur_obj_start_cam_event(UNUSED struct Object *obj, s32 cameraEvent);`
