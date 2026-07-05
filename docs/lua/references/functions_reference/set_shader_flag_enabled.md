
## [set_shader_flag_enabled](#set_shader_flag_enabled)

### Description
Enables a custom shader flag (`SHADER_FLAG_*`) for the renderer

### Lua Example
`set_shader_flag_enabled(flag, enabled)`

### Parameters
| Field | Type |
| ----- | ---- |
| flag | [enum ShaderFlag](constants.md#enum-ShaderFlag) |
| enabled | `boolean` |

### Returns
- None

### C Prototype
`void set_shader_flag_enabled(enum ShaderFlag flag, bool enabled);`
