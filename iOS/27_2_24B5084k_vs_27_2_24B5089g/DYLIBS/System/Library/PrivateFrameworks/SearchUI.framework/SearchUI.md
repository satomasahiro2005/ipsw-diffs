## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4800` | `0x36b0` | **`-0x1150`** |
| `__DATA_DIRTY.__objc_data` | `0x3208` | `0x4358` | **`+0x1150`** |
| `__DATA_DIRTY.__data` | `0x4b0` | `0xb50` | **`+0x6a0`** |
| `__DATA.__bss` | `0x1c60` | `0x1800` | **`-0x460`** |
| `__DATA_DIRTY.__bss` | `0xcd8` | `0x1128` | **`+0x450`** |
| `__DATA.__data` | `0x3384` | `0x2fec` | **`-0x398`** |
| `__AUTH.__data` | `0x7f0` | `0x4c0` | **`-0x330`** |
| `__AUTH_CONST.__cfstring` | `0x3420` | `0x33e0` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x2b28` | `0x2ae8` | **`-0x40`** |
| `__TEXT.__text` | `0xf71e8` | `0xf71c0` | **`-0x28`** |
| `__TEXT.__cstring` | `0x3b79` | `0x3b59` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x124d8` | `0x124e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4908` | `0x48f8` | **`-0x10`** |
| `__DATA.__common` | `0xe8` | `0xe0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2578` | `0x2570` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa2e8` | `0xa2e0` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x40` | `0x48` | **`+0x8`** |

### Other Changes

```diff

-685.1.2.0.0
+685.1.3.0.0

-  Functions: 7027
-  Symbols:   11523
-  CStrings:  833
+  Functions: 7024
+  Symbols:   11517
+  CStrings:  831
Symbols:
+ +[SearchUIUtilities isCurrentProcessHostingSpotlight]
+ -[SearchUICardSectionView contentViewLayoutMargins]
+ -[SearchUICardSectionView updateSecondaryCommandViewAlignmentInsets]
- +[SearchUIUtilities isCampoProcess]
- +[SearchUIUtilities isSpotlightProcess]
- _OBJC_CLASS_$_NSProcessInfo
- ___35+[SearchUIUtilities isCampoProcess]_block_invoke
- ___39+[SearchUIUtilities isSpotlightProcess]_block_invoke
- _isCampoProcess.isCampoProcess
- _isCampoProcess.onceToken
- _isSpotlightProcess.isSpotlightProcess
- _isSpotlightProcess.onceToken
CStrings:
- "Campo"
- "com.apple.Spotlight"
```
