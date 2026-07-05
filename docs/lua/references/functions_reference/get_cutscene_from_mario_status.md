
## [get_cutscene_from_mario_status](#get_cutscene_from_mario_status)

### Description
Gets the appropriate cutscene to play based on Mario's current gameplay state.
This function helps determine transitions for cinematic or scripted sequences

### Lua Example
`local integerValue = get_cutscene_from_mario_status(c)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |

### Returns
- `integer`

### C Prototype
`u8 get_cutscene_from_mario_status(struct Camera *c);`
