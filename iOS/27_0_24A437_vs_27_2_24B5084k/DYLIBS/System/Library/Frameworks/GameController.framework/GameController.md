## GameController

> `/System/Library/Frameworks/GameController.framework/GameController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1056c8` | `0x1058b0` | **`+0x1e8`** |
| `__AUTH_CONST.__cfstring` | `0xb4c0` | `0xb500` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x3894` | `0x38c4` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x10124` | `0x1014c` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x4d818` | `0x4d838` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa191` | `0xa1b1` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4f88` | `0x4f98` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4e98` | `0x4ea0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x16c0` | `0x16c4` | **`+0x4`** |

### Other Changes

```diff

-14.0.24.0.0
+14.1.2.0.0

-  Functions: 7731
-  Symbols:   14986
-  CStrings:  2437
+  Functions: 7734
+  Symbols:   14990
+  CStrings:  2439
Symbols:
+ -[GCDeviceSessionConfiguration setWantsTouchSyntheticMouse:]
+ -[GCDeviceSessionConfiguration wantsTouchSyntheticMouse]
+ -[GCMouse _becomeCurrent]
+ _OBJC_IVAR_$_GCDeviceSessionConfiguration._wantsTouchSyntheticMouse
CStrings:
+ "NSIsTouchNative"
+ "WantsTouchSyntheticMouse"
```
