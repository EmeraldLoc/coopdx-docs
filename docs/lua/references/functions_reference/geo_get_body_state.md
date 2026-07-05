
## [geo_get_body_state](#geo_get_body_state)

### Description
When used in a geo function, retrieve the MarioBodyState associated to the current processed object

### Lua Example
`local marioBodyStateValue = geo_get_body_state()`

### Parameters
- None

### Returns
- [MarioBodyState](structs.md#MarioBodyState)

### C Prototype
`struct MarioBodyState *geo_get_body_state(void);`
