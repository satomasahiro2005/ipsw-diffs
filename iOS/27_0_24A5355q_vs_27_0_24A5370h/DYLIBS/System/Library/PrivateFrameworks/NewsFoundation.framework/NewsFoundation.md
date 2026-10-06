## NewsFoundation

> `/System/Library/PrivateFrameworks/NewsFoundation.framework/NewsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85b8` | `0x859c` | **`-0x1c`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0
Functions:
~ -[NFPromiseSeal seal:error:resolution:] : 528 -> 524
~ -[NFEventManager attemptTriggersForCurrentEvent:] : 332 -> 328
~ -[NFEventManager handleOnceTrigger:event:] : 460 -> 456
~ -[NFEventManager handleAlwaysTrigger:event:] : 408 -> 404
~ -[NFMultiDelegate respondsToSelector:] : 360 -> 356
~ -[NFMultiDelegate methodSignatureForSelector:] : 396 -> 392
~ -[NFMultiDelegate forwardInvocation:] : 344 -> 340
```
