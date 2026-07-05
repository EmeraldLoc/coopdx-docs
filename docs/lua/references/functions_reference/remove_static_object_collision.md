
## [remove_static_object_collision](#remove_static_object_collision)

### Description
Removes all surfaces belonging to a static object collision and reclaims the SOC metadata

### Lua Example
`remove_static_object_collision(col)`

### Parameters
| Field | Type |
| ----- | ---- |
| col | [StaticObjectCollision](structs.md#StaticObjectCollision) |

### Returns
- None

### C Prototype
`void remove_static_object_collision(struct StaticObjectCollision *col);`
