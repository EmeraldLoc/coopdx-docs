
## [spawn_no_exit_star](#spawn_no_exit_star)

### Description
Spawns a Star that won't make Mario exit the level with an ID corresponding to the current object's first behavior parameter byte

### Lua Example
`local objectValue = spawn_no_exit_star(x, y, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| y | `number` |
| z | `number` |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object* spawn_no_exit_star(f32 x, f32 y, f32 z);`
