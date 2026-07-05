
## [get_door_save_file_flag](#get_door_save_file_flag)

### Description
Retrieves the save file flag associated with a door, based on the number of stars required to open it.
Used to check if the player has unlocked certain star doors or progressed far enough to access new areas

### Lua Example
`local integerValue = get_door_save_file_flag(door)`

### Parameters
| Field | Type |
| ----- | ---- |
| door | [Object](structs.md#Object) |

### Returns
- `integer`

### C Prototype
`u32 get_door_save_file_flag(struct Object *door);`
