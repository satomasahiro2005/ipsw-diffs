## ActivityUIServices

> `/System/Library/PrivateFrameworks/ActivityUIServices.framework/ActivityUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65aa0` | `0x66338` | **`+0x898`** |
| `__AUTH.__objc_data` | `0x66f0` | `0x6970` | **`+0x280`** |
| `__DATA.__bss` | `0x4708` | `0x4808` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xdc78` | `0xdcf8` | **`+0x80`** |
| `__TEXT.__const` | `0x4620` | `0x46a0` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x2828` | `0x2888` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3130` | `0x3190` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1cf8` | `0x1d58` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x10a0` | `0x10e0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1558` | `0x1588` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1f30` | `0x1f60` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x39f0` | `0x3a10` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x788` | `0x7a8` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x2d0` | `0x2e8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x11bc` | `0x11d4` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x140` | **`+0x14`** |
| `__DATA.__data` | `0x1a98` | `0x1aa8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x18c3` | `0x18d3` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1bc` | `0x1c0` | **`+0x4`** |

### Other Changes

```diff

-312.0.0.0.0
+312.100.0.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 3517
-  Symbols:   1995
-  CStrings:  270
+  Functions: 3538
+  Symbols:   2000
+  CStrings:  271
Symbols:
+ -[ACUISActivityHostViewController hostReferenceAngleMode]
+ -[ACUISActivityHostViewController hostReferenceAngle]
+ -[ACUISActivityHostViewController setHostReferenceAngle:mode:]
+ ___swift_closure_destructor.251Tm
+ _keypath_get.49Tm
+ _keypath_set.62Tm
+ _symbolic Su
+ _symbolic _____ So27UISSystemReferenceAngleModeV
- ___swift_closure_destructor.242Tm
- _keypath_get.45Tm
- _keypath_set.58Tm
CStrings:
+ "[%{public}s] Host reference angle changed to %{public}f degrees, mode %{public}lu"
```
