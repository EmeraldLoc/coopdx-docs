
## [obj_orient_graph](#obj_orient_graph)

### Description
Orients an object with the given normals, typically the surface under the object

### Lua Example
`obj_orient_graph(obj, normalX, normalY, normalZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| normalX | `number` |
| normalY | `number` |
| normalZ | `number` |

### Returns
- None

### C Prototype
`void obj_orient_graph(struct Object *obj, f32 normalX, f32 normalY, f32 normalZ);`
