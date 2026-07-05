
## [obj_resolve_collisions_and_turn](#obj_resolve_collisions_and_turn)

### Description
Resolves collisions and turns the current object towards `targetYaw` using `turnSpeed`

### Lua Example
`local integerValue = obj_resolve_collisions_and_turn(targetYaw, turnSpeed)`

### Parameters
| Field | Type |
| ----- | ---- |
| targetYaw | `integer` |
| turnSpeed | `integer` |

### Returns
- `integer`

### C Prototype
`s32 obj_resolve_collisions_and_turn(s16 targetYaw, s16 turnSpeed);`
