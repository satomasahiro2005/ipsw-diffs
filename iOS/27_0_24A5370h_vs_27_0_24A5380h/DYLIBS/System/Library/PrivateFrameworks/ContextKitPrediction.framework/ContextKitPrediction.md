## ContextKitPrediction

> `/System/Library/PrivateFrameworks/ContextKitPrediction.framework/ContextKitPrediction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92ec` | `0x9328` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x620` | `0x640` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xd0` | `0xc8` | **`-0x8`** |

### Other Changes

```diff

-305.0.0.0.0
+307.0.0.0.0

+  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary
Symbols:
+ _BiomeLibrary
- _OBJC_CLASS_$_BMUserFocusComputedModeStream
Functions:
~ -[CKContextRecentsCache initWithCacheConfiguration:] : 236 -> 272
~ -[CKContextRecentsCache _updateLatestFocusMode] : 408 -> 424
~ ___52-[CKContextRecentsCache _registerComputedModeStream]_block_invoke.61 -> ___52-[CKContextRecentsCache _registerComputedModeStream]_block_invoke.60 : 176 -> 184
```
