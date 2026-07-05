
## [save_file_get_sound_mode](#save_file_get_sound_mode)

### Description
Returns the current sound mode (e.g., stereo, mono) stored in the save file.
Useful for checking the audio output preferences when loading a save

### Lua Example
`local integerValue = save_file_get_sound_mode()`

### Parameters
- None

### Returns
- `integer`

### C Prototype
`u16 save_file_get_sound_mode(void);`
