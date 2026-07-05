
## [handle_save_menu](#handle_save_menu)

### Description
Handles interactions with the save menu after collecting a star/key. Checks the user's selection (e.g., Save and Continue) and performs the corresponding action, such as saving the file or returning Mario to idle

### Lua Example
`handle_save_menu(m)`

### Parameters
| Field | Type |
| ----- | ---- |
| m | [MarioState](structs.md#MarioState) |

### Returns
- None

### C Prototype
`void handle_save_menu(struct MarioState *m);`
