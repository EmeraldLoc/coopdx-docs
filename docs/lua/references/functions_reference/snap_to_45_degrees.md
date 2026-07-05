
## [snap_to_45_degrees](#snap_to_45_degrees)

### Description
Takes in an SM64 angle unit and returns the nearest 45 degree angle, also in SM64 angle units.
Useful when needing to align angles (camera, yaw, etc.)

### Lua Example
`local integerValue = snap_to_45_degrees(angle)`

### Parameters
| Field | Type |
| ----- | ---- |
| angle | `integer` |

### Returns
- `integer`

### C Prototype
`s32 snap_to_45_degrees(s16 angle);`
