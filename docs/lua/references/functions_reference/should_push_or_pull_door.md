
## [should_push_or_pull_door](#should_push_or_pull_door)

### Description
Determines whether Mario should push or pull a door when he interacts with it, based on his orientation and position.
Useful for animating door interactions realistically, depending on which side Mario approaches from

### Lua Example
`local integerValue = should_push_or_pull_door(m, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 should_push_or_pull_door(struct MarioState *m, struct Object *o);`
