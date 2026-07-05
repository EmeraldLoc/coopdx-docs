# MarioState

| Field | Type | Access |
| ----- | ---- | ------ |
| playerIndex | `integer` | read-only |
| input | `integer` |  |
| numCoins | `integer` |  |
| numStars | `integer` |  |
| numLives | `integer` |  |
| numKeys | `integer` |  |
| health | `integer` |  |
| hurtCounter | `integer` |  |
| healCounter | `integer` |  |
| isSnoring | `integer` |  |
| freeze | `integer` |  |
| cap | `integer` |  |
| capTimer | `integer` |  |
| invincTimer | `integer` |  |
| skipWarpInteractionsTimer | `integer` |  |
| squishTimer | `integer` |  |
| bounceSquishTimer | `integer` |  |
| knockbackTimer | `integer` |  |
| wallKickTimer | `integer` |  |
| doubleJumpTimer | `integer` |  |
| specialTripleJump | `integer` |  |
| fadeWarpOpacity | `integer` |  |
| visibleToObjects | `boolean` |  |
| wasNetworkVisible | `integer` |  |
| dialogId | `integer` | read-only |
| prevNumStarsForDialog | `integer` |  |
| unkB0 | `integer` |  |
| action | `integer` |  |
| prevAction | `integer` |  |
| actionArg | `integer` |  |
| actionTimer | `integer` |  |
| actionState | `integer` |  |
| flags | `integer` |  |
| quicksandDepth | `number` |  |
| controller | [Controller](Controller.md) | read-only |
| marioBodyState | [MarioBodyState](MarioBodyState.md) | read-only |
| character | [Character](Character.md) |  |
| terrainSoundAddend | `integer` |  |
| pos | [Vec3f](Vec3f.md) | read-only |
| nonInstantWarpPos | [Vec3f](Vec3f.md) | read-only |
| vel | [Vec3f](Vec3f.md) | read-only |
| slideVelX | `number` |  |
| slideVelZ | `number` |  |
| forwardVel | `number` |  |
| peakHeight | `number` |  |
| intendedMag | `number` |  |
| intendedYaw | `integer` |  |
| framesSinceA | `integer` |  |
| framesSinceB | `integer` |  |
| faceAngle | [Vec3s](Vec3s.md) | read-only |
| angleVel | [Vec3s](Vec3s.md) | read-only |
| slideYaw | `integer` |  |
| twirlYaw | `integer` |  |
| heldObj | [Object](Object.md) |  |
| heldByObj | [Object](Object.md) |  |
| interactObj | [Object](Object.md) |  |
| riddenObj | [Object](Object.md) |  |
| usedObj | [Object](Object.md) |  |
| marioObj | [Object](Object.md) | read-only |
| bubbleObj | [Object](Object.md) |  |
| collidedObjInteractTypes | `integer` |  |
| particleFlags | `integer` |  |
| animation | [MarioAnimation](MarioAnimation.md) |  |
| splineKeyframe | `Pointer` <`Vec4s`> |  |
| splineKeyframeFraction | `number` |  |
| splineState | `integer` |  |
| curAnimOffset | `number` |  |
| minimumBoneY | `number` |  |
| wall | [Surface](Surface.md) |  |
| ceil | [Surface](Surface.md) |  |
| floor | [Surface](Surface.md) |  |
| spawnInfo | [SpawnInfo](SpawnInfo.md) |  |
| area | [Area](Area.md) | read-only |
| statusForCamera | [PlayerCameraState](PlayerCameraState.md) | read-only |
| ceilHeight | `number` |  |
| floorHeight | `number` |  |
| wallNormal | [Vec3f](Vec3f.md) | read-only |
| unkC4 | `number` |  |
| floorAngle | `integer` |  |
| waterLevel | `integer` |  |
| currentRoom | `integer` |  |
