
## [vec3i_sum](#vec3i_sum)

### Description
Adds the components of two 3D integer vectors `a` and `b` and stores the result in `dest`

### Lua Example
`local vec3iValue = vec3i_sum(dest, a, b)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| a | [Vec3i](structs.md#Vec3i) |
| b | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_sum(VEC_OUT Vec3i dest, Vec3i a, Vec3i b);`
