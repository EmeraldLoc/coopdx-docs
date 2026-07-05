# Area

| Field | Type | Access |
| ----- | ---- | ------ |
| index | `integer` |  |
| flags | `integer` |  |
| terrainType | `integer` |  |
| root | [GraphNodeRoot](GraphNodeRoot.md) |  |
| terrainData | `Pointer` <`integer`> | read-only |
| surfaceRooms | `Pointer` <`integer`> | read-only |
| macroObjects | `Pointer` <`integer`> | read-only |
| warpNodes | [ObjectWarpNode](ObjectWarpNode.md) | read-only |
| paintingWarpNodes | [WarpNode](WarpNode.md) | read-only |
| instantWarps | [InstantWarp](InstantWarp.md) |  |
| objectSpawnInfos | [SpawnInfo](SpawnInfo.md) | read-only |
| camera | [Camera](Camera.md) |  |
| whirlpools | `Array` <`Whirlpool`> |  |
| dialog | `Array` <`integer`> |  |
| musicParam | `integer` |  |
| musicParam2 | `integer` |  |
| localAreaTimer | `integer` | read-only |
| macroObjectsAltered | `Pointer` <`integer`> | read-only |
| numRedCoins | `integer` |  |
| numSecrets | `integer` |  |
| nextSyncID | `integer` | read-only |
