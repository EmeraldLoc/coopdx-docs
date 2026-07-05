
## [warp_camera](#warp_camera)

### Description
Moves the camera to a specified warp destination.
This function handles transitions between levels or areas seamlessly

### Lua Example
`warp_camera(displacementX, displacementY, displacementZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| displacementX | `number` |
| displacementY | `number` |
| displacementZ | `number` |

### Returns
- None

### C Prototype
`void warp_camera(f32 displacementX, f32 displacementY, f32 displacementZ);`
