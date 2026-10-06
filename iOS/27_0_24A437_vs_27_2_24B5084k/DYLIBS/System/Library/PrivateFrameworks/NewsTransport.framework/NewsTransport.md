## NewsTransport

> `/System/Library/PrivateFrameworks/NewsTransport.framework/NewsTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2afc14` | `0x2aff90` | **`+0x37c`** |
| `__AUTH_CONST.__objc_const` | `0x4e318` | `0x4e358` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x37d7c` | `0x37dac` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x161a0` | `0x161c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x11698` | `0x116b8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x12014` | `0x1202a` | **`+0x16`** |
| `__TEXT.__unwind_info` | `0x5080` | `0x5088` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4094` | `0x4098` | **`+0x4`** |

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 19073
-  Symbols:   26337
-  CStrings:  2845
+  Functions: 19077
+  Symbols:   26342
+  CStrings:  2846
Symbols:
+ -[NTPBScoreProfileDebug groupFormationScore]
+ -[NTPBScoreProfileDebug hasGroupFormationScore]
+ -[NTPBScoreProfileDebug setGroupFormationScore:]
+ -[NTPBScoreProfileDebug setHasGroupFormationScore:]
+ OBJC_IVAR_$_NTPBScoreProfileDebug._groupFormationScore
CStrings:
+ "group_formation_score"
```
