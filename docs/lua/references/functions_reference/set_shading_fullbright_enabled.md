
## [set_shading_fullbright_enabled](#set_shading_fullbright_enabled)

### Description
Enables fullbright mode for shaded materials (`G_LIGHTING`.)
If a light color is completely black, the rendered color will default to the shade color.
This is for already fullbright materials that set their shade color to something and their light color to black.
This visually corrects rendering on materials such as Mario's emblem.
Useful for using the lighting engine and having entirely your own shading without the game's own systems
and compatibility with most models, not having to used specialized env/prim color approaches for example

### Lua Example
`set_shading_fullbright_enabled(enabled)`

### Parameters
| Field | Type |
| ----- | ---- |
| enabled | `boolean` |

### Returns
- None

### C Prototype
`void set_shading_fullbright_enabled(bool enabled);`
