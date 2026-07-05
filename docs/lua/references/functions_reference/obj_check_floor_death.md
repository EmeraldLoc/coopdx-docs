
## [obj_check_floor_death](#obj_check_floor_death)

### Description
Checks if `floor`'s type is burning or death plane and if so change the
current object's action accordingly

### Lua Example
`obj_check_floor_death(collisionFlags, floor)`

### Parameters
| Field | Type |
| ----- | ---- |
| collisionFlags | `integer` |
| floor | [Surface](structs.md#Surface) |

### Returns
- None

### C Prototype
`void obj_check_floor_death(s16 collisionFlags, struct Surface *floor);`
