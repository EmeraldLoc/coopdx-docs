
## [check_if_moving_over_floor](#check_if_moving_over_floor)

### Description
Checks if the current object is moving `distance` units over a floor and within a max distance to floor of `maxDistToFloor`

### Lua Example
`local integerValue = check_if_moving_over_floor(maxDistToFloor, distance)`

### Parameters
| Field | Type |
| ----- | ---- |
| maxDistToFloor | `number` |
| distance | `number` |

### Returns
- `integer`

### C Prototype
`s32 check_if_moving_over_floor(f32 maxDistToFloor, f32 distance);`
