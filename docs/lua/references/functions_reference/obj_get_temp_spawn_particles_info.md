
## [obj_get_temp_spawn_particles_info](#obj_get_temp_spawn_particles_info)

### Description
Returns a temporary particle spawn info pointer with its model loaded in from `modelId`

### Lua Example
`local spawnParticlesInfoValue = obj_get_temp_spawn_particles_info(modelId)`

### Parameters
| Field | Type |
| ----- | ---- |
| modelId | [enum ModelExtendedId](constants.md#enum-ModelExtendedId) |

### Returns
- [SpawnParticlesInfo](structs.md#SpawnParticlesInfo)

### C Prototype
`struct SpawnParticlesInfo* obj_get_temp_spawn_particles_info(enum ModelExtendedId modelId);`
