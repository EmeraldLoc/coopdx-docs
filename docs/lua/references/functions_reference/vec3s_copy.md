
## [vec3s_copy](#vec3s_copy)

### Description
Copies the contents of a 3D short integer vector (`src`) into another 3D short integer vector (`dest`)

### Lua Example
`local vec3sValue = vec3s_copy(dest, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| src | [Vec3s](structs.md#Vec3s) |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_copy(VEC_OUT Vec3s dest, Vec3s src);`
