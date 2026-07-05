
## [area_get_warp_node](#area_get_warp_node)

### Description
Finds a warp node in the current area by its ID. The warp node must exist in the list of warp nodes for the current area.
Useful for locating a specific warp point in the level, such as teleportation zones or connections to other areas

### Lua Example
`local objectWarpNodeValue = area_get_warp_node(id)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | `integer` |

### Returns
- [ObjectWarpNode](structs.md#ObjectWarpNode)

### C Prototype
`struct ObjectWarpNode *area_get_warp_node(u8 id);`
