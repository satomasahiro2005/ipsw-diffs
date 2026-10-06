## MediaSafetyNet

> `/System/Library/PrivateFrameworks/MediaSafetyNet.framework/MediaSafetyNet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2ac` | `0xa27c` | **`-0x30`** |

### Other Changes

```text
Functions:
~ ___MSNMonitorStartServerMode_block_invoke_2 : 976 -> 972
~ -[MSNPillDataSourceServer fetchPillRegistrationForProcess:withCompletion:] : 1320 -> 1312
~ _MSNMonitorBeginException : 468 -> 464
~ _MSNMonitorEndException : 468 -> 464
~ ___62-[MSNPillDataSourceServer listener:shouldAcceptNewConnection:]_block_invoke.38 : 364 -> 360
~ ___46+[MSNScopedExceptionsServer validEntitlements]_block_invoke : 336 -> 332
~ -[MSNScopedExceptionsServer listener:shouldAcceptNewConnection:] : 524 -> 520
~ ___64-[MSNScopedExceptionsServer listener:shouldAcceptNewConnection:]_block_invoke.79 : 476 -> 472
~ -[MSNScopedExceptionsServer isExceptionInEffect:] : 432 -> 428
~ +[MSNScopedExceptionsServer proxiesForException:] : 1152 -> 1144
```
