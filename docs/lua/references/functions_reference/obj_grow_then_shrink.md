
## [obj_grow_then_shrink](#obj_grow_then_shrink)

### Description
Begin by increasing the current object's scale by `scaleVel`, and slowly decreasing `scaleVel`.
Once the object starts to shrink, wait a bit, and then begin to scale the object toward `endScale`.
The first time it reaches below `shootFireScale` during this time, return 1.
Return -1 once it's reached endScale

### Lua Example
`local integerValue, scaleVel = obj_grow_then_shrink(scaleVel, shootFireScale, endScale)`

### Parameters
| Field | Type |
| ----- | ---- |
| scaleVel | `number` |
| shootFireScale | `number` |
| endScale | `number` |

### Returns
- `integer`
- `number`

### C Prototype
`s32 obj_grow_then_shrink(INOUT f32 *scaleVel, f32 shootFireScale, f32 endScale);`
