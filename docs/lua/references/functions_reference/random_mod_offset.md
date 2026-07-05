
## [random_mod_offset](#random_mod_offset)

### Description
Generates a random offset using step multiplied a value between 0 and `mod` (the random function goes to 65535 but wraps around to 0 at `mod`)

### Lua Example
`local integerValue = random_mod_offset(base, step, mod)`

### Parameters
| Field | Type |
| ----- | ---- |
| base | `integer` |
| step | `integer` |
| mod | `integer` |

### Returns
- `integer`

### C Prototype
`s16 random_mod_offset(s16 base, s16 step, s16 mod);`
