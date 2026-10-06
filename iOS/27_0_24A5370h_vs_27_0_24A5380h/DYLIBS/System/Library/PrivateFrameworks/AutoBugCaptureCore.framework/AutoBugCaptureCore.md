## AutoBugCaptureCore

> `/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77a24` | `0x77aec` | **`+0xc8`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x538` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1578` | `0x15c8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xc8b0` | `0xc8f0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5fac` | `0x5fcc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3728` | `0x3740` | **`+0x18`** |
| `__TEXT.__cstring` | `0x51d5` | `0x51e1` | **`+0xc`** |
| `__DATA.__bss` | `0x110` | `0x108` | **`-0x8`** |
| `__DATA.__data` | `0xd28` | `0xd30` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x690` | `0x698` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x288` | `0x290` | **`+0x8`** |

### Other Changes

```diff

-464.0.0.0.0
+467.0.0.0.0

-  Functions: 2255
-  Symbols:   4311
-  CStrings:  2277
+  Functions: 2258
+  Symbols:   4317
+  CStrings:  2278
Symbols:
+ -[ABCPreferences _startObservingInstalledProfilesIfNeeded]
+ -[ABCPreferences _stopObservingInstalledProfiles]
+ -[ABCPreferences _tearDownCheckProfilesTimer]
+ _OBJC_IVAR_$_ABCPreferences._checkProfilesTimerLock
+ _OBJC_IVAR_$_ABCPreferences._installedProfilesObservationLock
+ _kNetDiagOptDiagsUseGMI
CStrings:
+ "diagsusegmi"
```
