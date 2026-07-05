
## [vec3i_combine](#vec3i_combine)

### Description
Takes two 3D integer vectors `vecA` and `vecB`, multiplies them by `sclA` and `sclB` respectively, adds the scaled vectors together and stores the result in `dest`

### Lua Example
`local vec3iValue = vec3i_combine(dest, vecA, vecB, sclA, sclB)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Vec3i](structs.md#Vec3i) |
| vecA | [Vec3i](structs.md#Vec3i) |
| vecB | [Vec3i](structs.md#Vec3i) |
| sclA | `number` |
| sclB | `number` |

### Returns
- [Vec3i](structs.md#Vec3i)

### C Prototype
`Vec3ip vec3i_combine(VEC_OUT Vec3i dest, Vec3i vecA, Vec3i vecB, f32 sclA, f32 sclB);`
