
## [get_shader_flag_enabled](#get_shader_flag_enabled)

### Description
Gets if a custom shader flag (`SHADER_FLAG_*`) is enabled or not

### Lua Example
`local booleanValue = get_shader_flag_enabled(flag)`

### Parameters
| Field | Type |
| ----- | ---- |
| flag | [enum ShaderFlag](constants.md#enum-ShaderFlag) |

### Returns
- `boolean`

### C Prototype
`bool get_shader_flag_enabled(enum ShaderFlag flag);`
