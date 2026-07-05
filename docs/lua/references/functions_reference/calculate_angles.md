
## [calculate_angles](#calculate_angles)

### Description
Calculates and returns the pitch and yaw angles from one 3D position (`from`) to another (`to`)

### Lua Example
`local pitch, yaw = calculate_angles(from, to)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |

### Returns
- `integer`
- `integer`

### C Prototype
`void calculate_angles(Vec3f from, Vec3f to, RET s16 *pitch, RET s16 *yaw);`
