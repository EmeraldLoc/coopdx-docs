
## [obj_get_temp_water_droplet_params](#obj_get_temp_water_droplet_params)

### Description
Returns a temporary water droplet params pointer with its model and behavior loaded in from `modelId` and `behaviorId`

### Lua Example
`local waterDropletParamsValue = obj_get_temp_water_droplet_params(modelId, behaviorId)`

### Parameters
| Field | Type |
| ----- | ---- |
| modelId | [enum ModelExtendedId](constants.md#enum-ModelExtendedId) |
| behaviorId | [enum BehaviorId](constants.md#enum-BehaviorId) |

### Returns
- [WaterDropletParams](structs.md#WaterDropletParams)

### C Prototype
`struct WaterDropletParams* obj_get_temp_water_droplet_params(enum ModelExtendedId modelId, enum BehaviorId behaviorId);`
