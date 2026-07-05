
## [start_object_cutscene_without_focus](#start_object_cutscene_without_focus)

### Description
Starts a cutscene focused on an object without requiring focus to remain locked.
This is useful for dynamic events where the camera adjusts freely

### Lua Example
`local integerValue = start_object_cutscene_without_focus(cutscene)`

### Parameters
| Field | Type |
| ----- | ---- |
| cutscene | `integer` |

### Returns
- `integer`

### C Prototype
`u8 start_object_cutscene_without_focus(u8 cutscene);`
