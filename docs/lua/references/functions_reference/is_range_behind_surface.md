
## [is_range_behind_surface](#is_range_behind_surface)

### Description
Determines if a range is obstructed by a surface relative to the camera.
Returns true if the range is behind the specified surface

### Lua Example
`local integerValue = is_range_behind_surface(from, to, surf, range, surfType)`

### Parameters
| Field | Type |
| ----- | ---- |
| from | [Vec3f](structs.md#Vec3f) |
| to | [Vec3f](structs.md#Vec3f) |
| surf | [Surface](structs.md#Surface) |
| range | `integer` |
| surfType | `integer` |

### Returns
- `integer`

### C Prototype
`s32 is_range_behind_surface(Vec3f from, Vec3f to, struct Surface *surf, s16 range, s16 surfType);`
