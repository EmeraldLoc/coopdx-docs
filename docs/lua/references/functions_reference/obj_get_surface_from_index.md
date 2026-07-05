
## [obj_get_surface_from_index](#obj_get_surface_from_index)

### Description
Gets a surface corresponding to `index` from the surface pool buffer

### Lua Example
`local surfaceValue = obj_get_surface_from_index(o, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |
| index | `integer` |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface *obj_get_surface_from_index(struct Object *o, u32 index);`
