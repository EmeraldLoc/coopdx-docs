
## [is_within_100_units_of_mario](#is_within_100_units_of_mario)

### Description
Checks if a position is within 100 units of Mario's current position.
Returns true if the position is within the specified radius and false otherwise

### Lua Example
`local integerValue = is_within_100_units_of_mario(posX, posY, posZ)`

### Parameters
| Field | Type |
| ----- | ---- |
| posX | `number` |
| posY | `number` |
| posZ | `number` |

### Returns
- `integer`

### C Prototype
`s32 is_within_100_units_of_mario(f32 posX, f32 posY, f32 posZ);`
