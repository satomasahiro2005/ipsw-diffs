## AnnounceDaemon

> `/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55ef8` | `0x560dc` | **`+0x1e4`** |
| `__TEXT.__gcc_except_tab` | `0xabc` | `0xb0c` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x60` | `0x90` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x8d0` | `0x8d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x16c8` | `0x16c0` | **`-0x8`** |

### Other Changes

```diff

-328.0.0.0.0
+329.0.0.0.0

-  Symbols:   2852
+  Symbols:   2853
Symbols:
+ _RPOptionStatusFlags
Functions:
~ -[ANRapportConnection registerDailyRequest:] : 164 -> 280
~ -[ANRapportConnection _registerMessageRequestHandler] : 216 -> 340
~ -[ANRapportConnection _registerHomeLocationStatusRequestHandler] : 216 -> 340
~ -[ANCompanionConnection _registerForEvents] : 348 -> 468
```
