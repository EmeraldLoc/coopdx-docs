
## [cutscene_object](#cutscene_object)

### Description
Initiates a cutscene focusing on a specific object in the game world.
The camera transitions smoothly to the object, adapting its position as needed

### Lua Example
`local integerValue = cutscene_object(cutscene, o)`

### Parameters
| Field | Type |
| ----- | ---- |
| cutscene | `integer` |
| o | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`s16 cutscene_object(u8 cutscene, struct Object *o);`
