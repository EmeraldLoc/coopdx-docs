
## [vec3f_copy](#vec3f_copy)

### Description
Copies the contents of a 3D floating-point vector (`src`) into another 3D floating-point vector (`dest`)

### Lua Example
`local vec3fValue = vec3f_copy(dest, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| src | [Vec3f](structs.md#Vec3f) |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_copy(VEC_OUT Vec3f dest, Vec3f src);`
