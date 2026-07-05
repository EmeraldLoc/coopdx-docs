
## [obj_spawn_loot_coins](#obj_spawn_loot_coins)

### Description
Spawns loot coins from an object using the specified behavior, jitter, and model

### Lua Example
`obj_spawn_loot_coins(obj, numCoins, baseYVel, coinBehavior, posJitter, model)`

### Parameters
| Field | Type |
| ----- | ---- |
| obj | [Object](structs.md#Object) |
| numCoins | `integer` |
| baseYVel | `number` |
| coinBehavior | `Pointer` <`BehaviorScript`> |
| posJitter | `integer` |
| model | `integer` |

### Returns
- None

### C Prototype
`void obj_spawn_loot_coins(struct Object *obj, s32 numCoins, f32 baseYVel, const BehaviorScript *coinBehavior, s16 posJitter, s16 model);`
