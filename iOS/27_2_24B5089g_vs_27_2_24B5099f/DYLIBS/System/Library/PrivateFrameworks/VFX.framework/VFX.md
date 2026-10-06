## VFX

> `/System/Library/PrivateFrameworks/VFX.framework/VFX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7bf98` | `0xd7caa8` | **`+0xb10`** |
| `__TEXT.__eh_frame` | `0x287f8` | `0x288b8` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x2b148` | `0x2b1a0` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x91de0` | `0x91e08` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x13664` | `0x13688` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0x4c738` | `0x4c758` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x20884` | `0x2089c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb00` | `0xcb10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e60` | `0x1e68` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x210c` | `0x2110` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-233.40.2.0.0
+233.40.3.0.0

-  Functions: 68348
-  Symbols:   2066
+  Functions: 68380
+  Symbols:   2067
Symbols:
+ __UIWindowSceneDidUpdateEffectiveGeometryNotification
CStrings:
+ "233.40.3"
+ "Welcome to VFX 233.40.3 (Sep 26 2026 06:26:52)"
+ "\xb2"
- "233.40.2"
- "Welcome to VFX 233.40.2 (Sep 13 2026 21:01:30)"
- "\xb1"
```
