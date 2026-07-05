
## [rotate_in_yz](#rotate_in_yz)

### Description
Rotates a vector around the YZ-plane by a specified pitch angle.
The result is stored in the destination vector (`dst`).
Useful for vertical camera rotations or object transformations

### Lua Example
`rotate_in_yz(dst, src, pitch)`

### Parameters
| Field | Type |
| ----- | ---- |
| dst | [Vec3f](structs.md#Vec3f) |
| src | [Vec3f](structs.md#Vec3f) |
| pitch | `integer` |

### Returns
- None

### C Prototype
`void rotate_in_yz(VEC_OUT Vec3f dst, Vec3f src, s16 pitch);`
