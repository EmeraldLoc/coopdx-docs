
## [obj_resolve_object_collisions](#obj_resolve_object_collisions)

### Description
Resolves "collisions" with the current object and other objects by offsetting the current object's position. Returns TRUE and the target yaw if there is collision

### Lua Example
`local integerValue, targetYaw = obj_resolve_object_collisions()`

### Parameters
- None

### Returns
- `integer`
- `integer`

### C Prototype
`s32 obj_resolve_object_collisions(RET s32 *targetYaw);`
