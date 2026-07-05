
## [geo_get_mario_object](#geo_get_mario_object)

### Description
When used in a geo function, retrieve the Mario object associated to the current processed object if it is a valid Mario or mirror Mario, return `nil` otherwise

### Lua Example
`local objectValue = geo_get_mario_object()`

### Parameters
- None

### Returns
- [Object](structs.md#Object)

### C Prototype
`struct Object *geo_get_mario_object(void);`
