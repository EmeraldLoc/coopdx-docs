
## [smlua_text_utils_dialog_get](#smlua_text_utils_dialog_get)

### Description
Gets the DialogEntry struct for the given `dialogId`

### Lua Example
`local dialogEntryValue = smlua_text_utils_dialog_get(dialogId)`

### Parameters
| Field | Type |
| ----- | ---- |
| dialogId | [enum DialogId](constants.md#enum-DialogId) |

### Returns
- [DialogEntry](structs.md#DialogEntry)

### C Prototype
`struct DialogEntry* smlua_text_utils_dialog_get(enum DialogId dialogId);`
