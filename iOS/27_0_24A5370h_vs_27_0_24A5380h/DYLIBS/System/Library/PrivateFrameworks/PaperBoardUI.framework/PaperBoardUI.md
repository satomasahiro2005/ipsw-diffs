## PaperBoardUI

> `/System/Library/PrivateFrameworks/PaperBoardUI.framework/PaperBoardUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x42cd` | `0x4363` | **`+0x96`** |
| `__TEXT.__text` | `0x778f0` | `0x77978` | **`+0x88`** |
| `__DATA.__bss` | `0x450` | `0x470` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x20` | `—` | **`-0x20`** |
| `__TEXT.__cstring` | `0x7a3f` | `0x7a3d` | **`-0x2`** |

### Other Changes

```diff

-344.0.101.0.0
+347.102.0.0.0

-  Symbols:   6087
-  CStrings:  1403
+  Symbols:   6086
+  CStrings:  1404
Symbols:
- ___79-[PBUIPosterWallpaperViewController updateConfiguration:withAnimationSettings:]_block_invoke_6
CStrings:
+ "-[PBUIPosterWallpaperViewController updateConfiguration:withAnimationSettings:]_block_invoke"
+ "-[PBUIPosterWallpaperViewController updateConfiguration:withAnimationSettings:]_block_invoke_5"
+ "Jul  2 2026 13:04:06"
+ "[rdar://181158838] reconfigure self-seed: using _activeOrientation=%lu (window effectiveGeometry interfaceOrientation was %lu) windowScene=%{public}@"
- "-[PBUIPosterWallpaperViewController updateConfiguration:withAnimationSettings:]_block_invoke_2"
- "-[PBUIPosterWallpaperViewController updateConfiguration:withAnimationSettings:]_block_invoke_6"
- "Jun 16 2026 22:14:40"
```
