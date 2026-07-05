
## [obj_bounce_off_walls_edges_objects](#obj_bounce_off_walls_edges_objects)

### Description
Bounces the current object off of walls, edges, and objects. Returns TRUE and the target yaw if there is collision

### Lua Example
`local integerValue, targetYaw = obj_bounce_off_walls_edges_objects()`

### Parameters
- None

### Returns
- `integer`
- `integer`

### C Prototype
`s32 obj_bounce_off_walls_edges_objects(RET s32 *targetYaw);`
