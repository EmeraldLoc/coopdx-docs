
## [le_set_light_use_surface_normals](#le_set_light_use_surface_normals)

### Description
Sets whether a lighting engine point light will use a surface's normals to determine its brightness with `useSurfaceNormals`

### Lua Example
`le_set_light_use_surface_normals(id, useSurfaceNormals)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | `integer` |
| useSurfaceNormals | `boolean` |

### Returns
- None

### C Prototype
`void le_set_light_use_surface_normals(s16 id, bool useSurfaceNormals);`
