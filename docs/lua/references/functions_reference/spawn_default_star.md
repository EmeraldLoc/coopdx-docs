
## [spawn_default_star](#spawn_default_star)

### Description
Spawns a Star with an ID corresponding to the current object's first behavior parameter byte

### Lua Example
`local objectValue = spawn_default_star(x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object* spawn_default_star(f32 x, f32 y, f32 z);`
