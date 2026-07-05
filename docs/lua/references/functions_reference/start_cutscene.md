
## [start_cutscene](#start_cutscene)

### Description
Starts a cutscene based on the provided ID.
The camera transitions to predefined behaviors for the duration of the cutscene

### Lua Example
`start_cutscene(c, cutscene)`

### Parameters
| Field | Type |
| ----- | ---- |
| c | [Camera](structs.md#Camera) |
| cutscene | `integer` |

### Returns
- None

### C Prototype
`void start_cutscene(struct Camera *c, u8 cutscene);`
