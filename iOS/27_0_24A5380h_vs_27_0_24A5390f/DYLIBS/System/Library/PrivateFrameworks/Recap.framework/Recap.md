## Recap

> `/System/Library/PrivateFrameworks/Recap.framework/Recap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21fd0` | `0x22174` | **`+0x1a4`** |
| `__AUTH_CONST.__objc_const` | `0x53b8` | `0x5438` | **`+0x80`** |
| `__DATA.__bss` | `0x170` | `0x148` | **`-0x28`** |
| `__DATA_DIRTY.__bss` | `0xa8` | `0xd0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x34e0` | `0x34f8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3a8` | `0x3b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e48` | `0x1e58` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x750` | `0x758` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9f0` | `0x9f8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-197.0.0.0.0
+198.0.0.0.0

-  Functions: 1024
-  Symbols:   2133
-  CStrings:  395
+  Functions: 1026
+  Symbols:   2140
+  CStrings:  396
Symbols:
+ -[RCPSyntheticFluidSwipeEventStream appendVelocityChildToEvent:]
+ -[RCPSyntheticFluidSwipeEventStream trackVelocityRate]
+ _IOHIDEventCreateVelocityEvent
+ _OBJC_IVAR_$_RCPEventStreamRecorder._rawEventsLock
+ _OBJC_IVAR_$_RCPSyntheticFluidSwipeEventStream._latestVelocityRate
+ _OBJC_IVAR_$_RCPSyntheticFluidSwipeEventStream._previousEventProgress
+ _OBJC_IVAR_$_RCPSyntheticFluidSwipeEventStream._previousEventTimeOffset
CStrings:
+ "!!"
+ "03:28:05"
+ "Jul  8 2026"
- "04:42:07"
- "Jun 23 2026"
```
