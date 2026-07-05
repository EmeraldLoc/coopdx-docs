
## [smlua_text_utils_dialog_is_replaced](#smlua_text_utils_dialog_is_replaced)

### Description
Returns whether the dialog with the given ID has been replaced

### Lua Example
`local booleanValue = smlua_text_utils_dialog_is_replaced(dialogId)`

### Parameters
| Field | Type |
| ----- | ---- |
| dialogId | [enum DialogId](constants.md#enum-DialogId) |

### Returns
- `boolean`

### C Prototype
`bool smlua_text_utils_dialog_is_replaced(enum DialogId dialogId);`
