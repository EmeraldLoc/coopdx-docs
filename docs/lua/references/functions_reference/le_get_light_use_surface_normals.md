
## [le_get_light_use_surface_normals](#le_get_light_use_surface_normals)

### Description
Gets whether a lighting engine point light will use a surface's normals to determine its brightness with `useSurfaceNormals`

### Lua Example
`local booleanValue = le_get_light_use_surface_normals(id)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | `integer` |

### Returns
- `boolean`

### C Prototype
`bool le_get_light_use_surface_normals(s16 id);`
