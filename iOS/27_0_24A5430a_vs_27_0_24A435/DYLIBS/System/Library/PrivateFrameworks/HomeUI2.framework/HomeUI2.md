## HomeUI2

> `/System/Library/PrivateFrameworks/HomeUI2.framework/HomeUI2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f5144` | `0x4f6af0` | **`+0x19ac`** |
| `__TEXT.__eh_frame` | `0x14c00` | `0x14e20` | **`+0x220`** |
| `__AUTH_CONST.__const` | `0x179b8` | `0x17b98` | **`+0x1e0`** |
| `__TEXT.__swift5_capture` | `0x4e74` | `0x4f70` | **`+0xfc`** |
| `__TEXT.__unwind_info` | `0xcda0` | `0xce28` | **`+0x88`** |
| `__TEXT.__const` | `0x27754` | `0x277d4` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6806` | `0x6836` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x4ea0` | `0x4eb8` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0xc70` | `0xc84` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x628` | `0x638` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x5e4` | `0x5f4` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xac8` | `0xac0` | **`-0x8`** |

### Other Changes

```diff

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 18289
-  Symbols:   6319
-  CStrings:  1068
+  Functions: 18320
+  Symbols:   6320
+  CStrings:  1069
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_internalBuild
+ ___swift_closure_destructor.14Tm
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.12Tm
CStrings:
+ "exclamationmark.bubble"
```
