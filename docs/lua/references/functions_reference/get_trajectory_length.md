
## [get_trajectory_length](#get_trajectory_length)

### Description
Gets the number of steps in a trajectory until the end marker

### Lua Example
`local integerValue = get_trajectory_length(trajectory)`

### Parameters
| Field | Type |
| ----- | ---- |
| trajectory | `Pointer` <`Trajectory`> |

### Returns
- `integer`

### C Prototype
`s32 get_trajectory_length(Trajectory* trajectory);`
