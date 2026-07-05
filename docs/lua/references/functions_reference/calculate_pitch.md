
## [calculate_pitch](#calculate_pitch)

### Description
Calculates the pitch angle (rotation around the X-axis) from one 3D point (`from`) to another (`to`).
Returns the pitch as a signed 16-bit integer

### Lua Example
`local integerValue = calculate_pitch(from, to)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |

### Returns
- `integer`

### C Prototype
`s16 calculate_pitch(Vec3f from, Vec3f to);`
