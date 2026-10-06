## GameControllerServer

> `/System/Library/PrivateFrameworks/GameControllerServer.framework/GameControllerServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x102c4` | `0x10328` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x2318` | `0x2338` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1864` | `0x1870` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x9c8` | `0x9d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x18c` | `0x190` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-14.0.21.0.0
+14.0.24.0.0

-  Symbols:   1005
+  Symbols:   1006
Symbols:
+ _OBJC_IVAR_$__GCHapticLogicalDevice._hapticsPlaying
Functions:
~ -[_GCHapticServerManager processActiveEventsForStartTime:endTime:] : 2440 -> 2532
~ -[_GCHapticLogicalDevice stopAllHaptics] : 212 -> 220
```
