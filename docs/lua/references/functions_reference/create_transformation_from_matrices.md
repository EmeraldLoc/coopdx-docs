
## [create_transformation_from_matrices](#create_transformation_from_matrices)

### Description
Combines two transformation matrices into a single result matrix

### Lua Example
`create_transformation_from_matrices(dest, src1, src2)`

### Parameters
| Field | Type |
| ----- | ---- |
| dest | [Mat4](structs.md#Mat4) |
| src1 | [Mat4](structs.md#Mat4) |
| src2 | [Mat4](structs.md#Mat4) |

### Returns
- None

### C Prototype
`void create_transformation_from_matrices(VEC_OUT Mat4 dest, Mat4 src1, Mat4 src2);`
