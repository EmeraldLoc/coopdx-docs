
## [area_get_warp_node_from_params](#area_get_warp_node_from_params)

### Description
Finds a warp node in the current area using parameters from the provided object. The object's behavior parameters are used to determine the warp node ID.
Useful for associating an object (like a door or warp pipe) with its corresponding warp node in the area

### Lua Example
`local objectWarpNodeValue = area_get_warp_node_from_params(o)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |

### Returns
- [ObjectWarpNode](structs.md#ObjectWarpNode)

### C Prototype
`struct ObjectWarpNode *area_get_warp_node_from_params(struct Object *o);`
