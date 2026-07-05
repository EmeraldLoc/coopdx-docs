
## [rotate_in_xz](#rotate_in_xz)

### Description
Rotates a vector around the XZ-plane by a specified yaw angle.
The result is stored in the destination vector (`dst`).
Useful for rotating camera positions or object coordinates horizontally

### Lua Example
`rotate_in_xz(dst, src, yaw)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | [Vec3f](structs.md#Vec3f) |
| src | [Vec3f](structs.md#Vec3f) |
| yaw | `integer` |

### Returns
- None

### C Prototype
`void rotate_in_xz(VEC_OUT Vec3f dst, Vec3f src, s16 yaw);`
