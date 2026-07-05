
## [interact_cannon_base](#interact_cannon_base)

### Description
Handles interaction when Mario touches a cannon base. If the cannon is ready, Mario enters the cannon, triggering a special action and camera behavior.
Useful for transitioning to cannon-aiming mode and enabling cannon travel within levels

### Lua Example
`local integerValue = interact_cannon_base(m, interactType, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| interactType | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 interact_cannon_base(struct MarioState *m, UNUSED u32 interactType, struct Object *o);`
