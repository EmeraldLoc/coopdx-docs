# GraphNodeObject

| Field | Type | Access |
| ----- | ---- | ------ |
| node | [GraphNode](GraphNode.md) | read-only |
| sharedChild | [GraphNode](GraphNode.md) | read-only |
| throwMatrix | `Pointer` <`Mat4`> |  |
| throwMatrixPrev | `Pointer` <`Mat4`> | read-only |
| prevThrowMatrix | [Mat4](Mat4.md) | read-only |
| angle | [Vec3s](Vec3s.md) | read-only |
| prevAngle | [Vec3s](Vec3s.md) | read-only |
| pos | [Vec3f](Vec3f.md) | read-only |
| prevPos | [Vec3f](Vec3f.md) | read-only |
| shadowPos | [Vec3f](Vec3f.md) | read-only |
| prevShadowPos | [Vec3f](Vec3f.md) | read-only |
| scale | [Vec3f](Vec3f.md) | read-only |
| prevScale | [Vec3f](Vec3f.md) | read-only |
| cameraToObject | [Vec3f](Vec3f.md) | read-only |
| prevTimestamp | `integer` | read-only |
| prevShadowPosTimestamp | `integer` | read-only |
| prevScaleTimestamp | `integer` | read-only |
| prevThrowMatrixTimestamp | `integer` | read-only |
| skipInterpolationTimestamp | `integer` | read-only |
| animInfo | [AnimInfo](AnimInfo.md) | read-only |
| areaIndex | `integer` |  |
| activeAreaIndex | `integer` |  |
| shadowInvisible | `boolean` |  |
| disableAutomaticShadowPos | `boolean` |  |
| skipInViewCheck | `boolean` |  |
| inited | `boolean` |  |
