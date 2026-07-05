
## [area_create_warp_node](#area_create_warp_node)

### Description
Creates a warp node in the current level and area with id `id` that goes to the warp node `destNode` in level `destLevel` and area `destArea`, and attach it to the object `o`.
To work properly, object `o` must be able to trigger a warp (for example, with interact type set to `INTERACT_WARP`.)
`checkpoint` should be set only to WARP_NO_CHECKPOINT (0x00) or WARP_CHECKPOINT (0x80.) If `checkpoint` is set to `0x80`, Mario will warp directly to this node if he enters the level again (after a death for example)

### Lua Example
`local objectWarpNodeValue = area_create_warp_node(id, destLevel, destArea, destNode, checkpoint, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| id | `integer` |
| destLevel | `integer` |
| destArea | `integer` |
| destNode | `integer` |
| checkpoint | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- [ObjectWarpNode](structs.md#ObjectWarpNode)

### C Prototype
`struct ObjectWarpNode *area_create_warp_node(u8 id, u8 destLevel, u8 destArea, u8 destNode, u8 checkpoint, struct Object *o);`
