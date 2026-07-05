
## [set_object_respawn_info_bits](#set_object_respawn_info_bits)

### Description
Runs an OR operator on the `obj`'s respawn info with `bits` << 8. If `bits` is 0xFF, this prevents the object from respawning after leaving and re-entering the area

### Lua Example
`set_object_respawn_info_bits(obj, bits)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| bits | `integer` |

### Returns
- None

### C Prototype
`void set_object_respawn_info_bits(struct Object *obj, u8 bits);`
