
## [load_static_object_collision](#load_static_object_collision)

### Description
Loads the object's collision data into static collision.
You may run this only once to capture the object's collision at that frame.

### Lua Example
`local staticObjectCollisionValue = load_static_object_collision()`

### Parameters
- None

### Returns
- [StaticObjectCollision](structs.md#StaticObjectCollision)

### C Prototype
`struct StaticObjectCollision *load_static_object_collision();`
