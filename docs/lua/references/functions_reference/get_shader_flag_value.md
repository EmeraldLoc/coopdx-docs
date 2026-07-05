
## [get_shader_flag_value](#get_shader_flag_value)

### Description
Gets a value for one of the custom shader flags (`SHADER_FLAG_*`)

### Lua Example
`local numberValue = get_shader_flag_value(flag)`

### Parameters
| Field | Type |
| ----- | ---- |
| flag | [enum ShaderFlag](constants.md#enum-ShaderFlag) |

### Returns
- `number`

### C Prototype
`f32 get_shader_flag_value(enum ShaderFlag flag);`
