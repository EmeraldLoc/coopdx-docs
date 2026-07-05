
## [initiate_warp](#initiate_warp)

### Description
Initiates a warp to `destLevel` in `destArea` at `destWarpNode` with `arg`. This function is unstable and it's generally recommended to use `warp_to_level` instead

### Lua Example
`initiate_warp(destLevel, destArea, destWarpNode, arg)`

### Parameters
| Field | Type |
| ----- | ---- |
| destLevel | `integer` |
| destArea | `integer` |
| destWarpNode | `integer` |
| arg | `integer` |

### Returns
- None

### C Prototype
`void initiate_warp(s16 destLevel, s16 destArea, s16 destWarpNode, s32 arg);`
