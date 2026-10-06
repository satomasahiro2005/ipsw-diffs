## DistributedTimersDaemon

> `/System/Library/PrivateFrameworks/DistributedTimersDaemon.framework/DistributedTimersDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d3e8` | `0x8e580` | **`+0x1198`** |
| `__TEXT.__oslogstring` | `0x1ff1` | `0x2091` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x1580` | `0x15a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1978` | `0x1990` | **`+0x18`** |
| `__DATA.__data` | `0x1150` | `0x1160` | **`+0x10`** |
| `__TEXT.__const` | `0x2708` | `0x2718` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x889` | `0x899` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa44` | `0xa50` | **`+0xc`** |
| `__TEXT.__eh_frame` | `0x4c78` | `0x4c70` | **`-0x8`** |

### Other Changes

```diff

-520.0.0.0.0
+524.0.16.0.0

-  Functions: 1793
+  Functions: 1797

-  CStrings:  269
+  CStrings:  271
CStrings:
+ "Server modification: alarm removed locally, ignoring re-add, id=%s"
+ "Server modification: timer removed locally, ignoring re-add, id=%s"
+ "removeAlarm: not found, %s"
+ "removeTimer: not found, %s"
- "removeAlarm: unknown, %s"
- "removeTimer: unknown, %s"
```
