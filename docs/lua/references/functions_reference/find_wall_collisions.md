
## [find_wall_collisions](#find_wall_collisions)

### Description
Detects wall collisions at a given position and adjusts the position based on the walls found.
Returns the number of wall collisions detected

### Lua Example
`local integerValue = find_wall_collisions(colData)`

### Parameters
| Field | Type |
| ----- | ---- |
| colData | [WallCollisionData](structs.md#WallCollisionData) |

### Returns
- `integer`

### C Prototype
`s32 find_wall_collisions(struct WallCollisionData *colData);`
