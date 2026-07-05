
## [spawn_water_droplet](#spawn_water_droplet)

### Description
Spawns a water droplet object with the specified parameters

### Lua Example
`local objectValue = spawn_water_droplet(parent, params)`

### Parameters
| Field | Type |
| ----- | ---- |
| parent | [Object](structs.md#Object) |
| params | [WaterDropletParams](structs.md#WaterDropletParams) |

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *spawn_water_droplet(struct Object *parent, struct WaterDropletParams *params);`
