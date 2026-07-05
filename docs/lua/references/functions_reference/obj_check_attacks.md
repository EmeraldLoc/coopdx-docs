
## [obj_check_attacks](#obj_check_attacks)

### Description
Checks the current object's interaction status and sets action to `attackedMarioAction` if Mario has been attacked and runs `obj_die_if_health_non_positive()` if the object is attacked by Mario. Sets the hitbox parameters and resets interaction status to 0

### Lua Example
`local integerValue = obj_check_attacks(hitbox, attackedMarioAction)`

### Parameters
| Field | Type |
| ----- | ---- |
| hitbox | [ObjectHitbox](structs.md#ObjectHitbox) |
| attackedMarioAction | `integer` |

### Returns
- `integer`

### C Prototype
`s32 obj_check_attacks(struct ObjectHitbox *hitbox, s32 attackedMarioAction);`
