
## [vec3i_copy](#vec3i_copy)

### Description
Copies the contents of a 3D integer vector (`src`) into another 3D integer vector (`dest`)

### Lua Example
`local vec3iValue = vec3i_copy(dest, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| src | [Vec3i](structs.md#Vec3i) |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_copy(VEC_OUT Vec3i dest, Vec3i src);`
