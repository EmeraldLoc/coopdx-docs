
## [smlua_model_util_get_id](#smlua_model_util_get_id)

### Description
Gets the extended model ID for the `name` of a `GeoLayout`

### Lua Example
`local enumValue = smlua_model_util_get_id(name)`

### Parameters
| Field | Type |
| ----- | ---- |
| name | `string` |

### Returns
- [enum ModelExtendedId](constants.md#enum-ModelExtendedId)

### C Prototype
`enum ModelExtendedId smlua_model_util_get_id(const char* name);`
