
## [get_mario_cap_flag](#get_mario_cap_flag)

### Description
Determines the type of cap an object represents. Depending on the object's behavior, it returns a cap type (normal, metal, wing, vanish).
Useful for handling the logic of picking up, wearing, or losing different kinds of caps

### Lua Example
`local integerValue = get_mario_cap_flag(capObject)`

### Parameters
| Field | Type |
| ----- | ---- |
| capObject | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 get_mario_cap_flag(struct Object *capObject);`
