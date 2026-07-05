
## [vec3f_combine](#vec3f_combine)

### Description
Takes two 3D floating-point vectors `vecA` and `vecB`, multiplies them by `sclA` and `sclB` respectively, adds the scaled vectors together and stores the result in `dest`

### Lua Example
`local vec3fValue = vec3f_combine(dest, vecA, vecB, sclA, sclB)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3f](structs.md#Vec3f) |
| vecA | [Vec3f](structs.md#Vec3f) |
| vecB | [Vec3f](structs.md#Vec3f) |
| sclA | `number` |
| sclB | `number` |

### Returns
- [Vec3f](structs.md#Vec3f)

### C Prototype
`Vec3fp vec3f_combine(VEC_OUT Vec3f dest, Vec3f vecA, Vec3f vecB, f32 sclA, f32 sclB);`
