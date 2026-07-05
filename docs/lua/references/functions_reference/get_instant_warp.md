
## [get_instant_warp](#get_instant_warp)

### Description
Gets an instant warp from the current area's instant warp array (0-3)

### Lua Example
`local instantWarpValue = get_instant_warp(index)`

### Parameters
| Field | Type |
| ----- | ---- |
| index | `integer` |

### Returns
- [InstantWarp](structs.md#InstantWarp)

### C Prototype
`struct InstantWarp *get_instant_warp(u8 index);`
