
## [execute_mario_action](#execute_mario_action)

### Description
Main driver for Mario's behavior. Executes the current action group (stationary, moving, airborne, etc.) in a loop until no further action changes are necessary

### Lua Example
`local integerValue = execute_mario_action(o)`

### Parameters
| Field | Type |
| ----- | ---- |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`s32 execute_mario_action(UNUSED struct Object *o);`
