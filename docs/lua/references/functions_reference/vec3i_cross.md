
## [vec3i_cross](#vec3i_cross)

### Description
Computes the cross product of two 3D integer vectors `a` and `b` and stores the result in `dest`

### Lua Example
`local vec3iValue = vec3i_cross(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| a | [Vec3i](structs.md#Vec3i) |
| b | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_cross(VEC_OUT Vec3i dest, Vec3i a, Vec3i b);`
