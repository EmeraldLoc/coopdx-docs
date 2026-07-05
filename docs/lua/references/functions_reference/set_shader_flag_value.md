
## [set_shader_flag_value](#set_shader_flag_value)

### Description
Sets a value for one of the custom shader flags (`SHADER_FLAG_*`) for the renderer

### Lua Example
`set_shader_flag_value(flag, value)`

### Parameters
| Field | Type |
| ----- | ---- |
| flag | [enum ShaderFlag](constants.md#enum-ShaderFlag) |
| value | `number` |

### Returns
- None

### C Prototype
`void set_shader_flag_value(enum ShaderFlag flag, f32 value);`
