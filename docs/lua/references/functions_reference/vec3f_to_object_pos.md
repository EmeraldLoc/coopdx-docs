
## [vec3f_to_object_pos](#vec3f_to_object_pos)

### Description
Converts a `Vec3f` position to an object's internal format.
Useful for syncing 3D positions between objects and the game world

### Lua Example
`vec3f_to_object_pos(o, src)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| src | [Vec3f](structs.md#Vec3f) |

### Returns
- None

### C Prototype
`void vec3f_to_object_pos(struct Object *o, Vec3f src);`
