
## [cur_obj_play_sound_and_rumble_if_visible](#cur_obj_play_sound_and_rumble_if_visible)

### Description
Plays a sound if the current object is visible and queues rumble for the following sounds: `SOUND_OBJ_BOWSER_WALK`, `SOUND_OBJ_POUNDING_LOUD`, `SOUND_OBJ_WHOMP_LOWPRIO`

### Lua Example
`cur_obj_play_sound_and_rumble_if_visible(soundMagic)`

### Parameters
| Field | Type |
| ----- | ---- |
| soundMagic | `integer` |

### Returns
- None

### C Prototype
`void cur_obj_play_sound_and_rumble_if_visible(s32 soundMagic);`
