
## [find_poison_gas_level](#find_poison_gas_level)

### Description
Finds the height of the poison gas at a given position (x, z), if the position is within a gas region.
If no gas is found, returns the default height of `gLevelValues.floorLowerLimit`(-11000 by default)

### Lua Example
`local numberValue = find_poison_gas_level(x, z)`

### Parameters
| Field | Type |
| ----- | ---- |
| x | `number` |
| z | `number` |

### Returns
- `number`

### C Prototype
`f32 find_poison_gas_level(f32 x, f32 z);`
