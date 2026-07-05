
## [cutscene_spawn_obj](#cutscene_spawn_obj)

### Description
Spawns an object as part of a cutscene, such as props or interactive elements.
Returns the spawned object's reference for further manipulation

### Lua Example
`local integerValue = cutscene_spawn_obj(obj, frame)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | `integer` |
| frame | `integer` |

### Returns
- `integer`

### C Prototype
`s32 cutscene_spawn_obj(u32 obj, s16 frame);`
