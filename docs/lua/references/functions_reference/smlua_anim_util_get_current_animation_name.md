
## [smlua_anim_util_get_current_animation_name](#smlua_anim_util_get_current_animation_name)

### Description
Gets the name of the current animation playing on `obj`, returns `nil` if there's no name

### Lua Example
`local stringValue = smlua_anim_util_get_current_animation_name(obj)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |

### Returns
- `string`

### C Prototype
`const char *smlua_anim_util_get_current_animation_name(struct Object *obj);`
