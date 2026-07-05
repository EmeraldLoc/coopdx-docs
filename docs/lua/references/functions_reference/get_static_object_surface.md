
## [get_static_object_surface](#get_static_object_surface)

### Description
Gets a surface corresponding to `index` from the static object collision

### Lua Example
`local surfaceValue = get_static_object_surface(col, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| col | [StaticObjectCollision](structs.md#StaticObjectCollision) |
| index | `integer` |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface *get_static_object_surface(struct StaticObjectCollision *col, u32 index);`
