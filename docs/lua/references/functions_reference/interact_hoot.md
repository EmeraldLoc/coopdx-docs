
## [interact_hoot](#interact_hoot)

### Description
Handles interaction with Hoot, the owl. If Mario can grab onto Hoot, this sets Mario onto a riding action, allowing him to fly around the level.
Useful for special traversal mechanics and shortcuts within a course

### Lua Example
`local integerValue = interact_hoot(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_hoot(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
