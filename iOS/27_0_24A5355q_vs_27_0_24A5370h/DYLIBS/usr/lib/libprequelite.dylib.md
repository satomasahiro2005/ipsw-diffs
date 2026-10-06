## libprequelite.dylib

> `/usr/lib/libprequelite.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2f8` | `0xd2e0` | **`-0x18`** |

### Other Changes

```diff

-158.0.0.0.0
+160.0.0.0.0
Functions:
~ -[PQLStatement(Swift) bindFromArray:db:] : 1196 -> 1192
~ -[PQLConnection _clearCleanupCacheQueueIfNeeded] : 520 -> 516
~ ___40-[PQLConnection _fireFlushNotifications]_block_invoke : 324 -> 320
~ -[PQLStatement bindArguments:db:] : 792 -> 788
~ -[PQLFormatInjection bindWithStatement:startingAtIndex:] : 548 -> 544
~ ___21-[PQLConnection init]_block_invoke : 492 -> 488
```
