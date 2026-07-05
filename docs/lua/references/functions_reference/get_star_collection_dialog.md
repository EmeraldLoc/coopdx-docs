
## [get_star_collection_dialog](#get_star_collection_dialog)

### Description
Determines which (if any) dialog to show when Mario collects a star. Checks milestone star counts against `prevNumStarsForDialog`, and returns a dialog ID if a milestone is reached. Otherwise, returns 0

### Lua Example
`local integerValue = get_star_collection_dialog(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- `integer`

### C Prototype
`s32 get_star_collection_dialog(struct MarioState *m);`
