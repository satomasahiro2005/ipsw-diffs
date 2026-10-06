## AppleIDSetupDaemon

> `/System/Library/PrivateFrameworks/AppleIDSetupDaemon.framework/AppleIDSetupDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b62d4` | `0x1b6758` | **`+0x484`** |
| `__TEXT.__const` | `0x49b4` | `0x4a64` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x3da0` | `0x3e20` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x117e` | `0x11ee` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x1e30` | `0x1e90` | **`+0x60`** |
| `__TEXT.__cstring` | `0xb52` | `0xb22` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1000` | `0x1030` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x8a8` | `0x8c8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1760` | `0x1748` | **`-0x18`** |

### Other Changes

```diff

-125.0.0.0.0
+128.1.1.0.0

-  Functions: 4025
-  Symbols:   1094
-  CStrings:  755
+  Functions: 4023
+  Symbols:   1091
+  CStrings:  754
Symbols:
+ ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.51Tm
- _swift_task_deinitOnExecutor
- _swift_task_isCurrentExecutor
- _swift_task_reportUnexpectedExecutor
CStrings:
- "AppleIDSetupDaemon/AgeMigrationService.swift"
```
