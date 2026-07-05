
## [vec3s_combine](#vec3s_combine)

### Description
Takes two 3D short integer vectors `vecA` and `vecB`, multiplies them by `sclA` and `sclB` respectively, adds the scaled vectors together and stores the result in `dest`

### Lua Example
`local vec3sValue = vec3s_combine(dest, vecA, vecB, sclA, sclB)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3s](structs.md#Vec3s) |
| vecA | [Vec3s](structs.md#Vec3s) |
| vecB | [Vec3s](structs.md#Vec3s) |
| sclA | `number` |
| sclB | `number` |

### Returns
- [Vec3s](structs.md#Vec3s)

### C Prototype
`Vec3sp vec3s_combine(VEC_OUT Vec3s dest, Vec3s vecA, Vec3s vecB, f32 sclA, f32 sclB);`
