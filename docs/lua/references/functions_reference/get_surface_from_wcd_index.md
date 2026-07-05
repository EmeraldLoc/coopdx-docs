
## [get_surface_from_wcd_index](#get_surface_from_wcd_index)

### Description
Gets the surface corresponding to `index` from `wcd`

### Lua Example
`local surfaceValue = get_surface_from_wcd_index(wcd, index)`

### Parameters
| Field | Type |
| ----- | ---- |
| wcd | [WallCollisionData](structs.md#WallCollisionData) |
| index | `integer` |

### Returns
- [Surface](structs.md#Surface)

### C Prototype
`struct Surface* get_surface_from_wcd_index(struct WallCollisionData* wcd, s8 index);`
