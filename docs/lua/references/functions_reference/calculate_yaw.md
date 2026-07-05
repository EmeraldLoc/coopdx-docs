
## [calculate_yaw](#calculate_yaw)

### Description
Determines the yaw angle (rotation around the Y-axis) from one 3D position (`from`) to another (`to`).
Returns the yaw as a signed 16-bit integer

### Lua Example
`local integerValue = calculate_yaw(from, to)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |

### Returns
- `integer`

### C Prototype
`s16 calculate_yaw(Vec3f from, Vec3f to);`
