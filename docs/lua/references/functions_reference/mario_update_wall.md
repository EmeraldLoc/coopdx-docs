
## [mario_update_wall](#mario_update_wall)

### Description
Updates Mario's wall information based on wall collisions (`WallCollisionData`). Chooses the most relevant wall depending on the level's collision fix settings

### Lua Example
`mario_update_wall(m, wcd)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |
| wcd | [WallCollisionData](structs.md#WallCollisionData) |

### Returns
- None

### C Prototype
`void mario_update_wall(struct MarioState* m, struct WallCollisionData* wcd);`
