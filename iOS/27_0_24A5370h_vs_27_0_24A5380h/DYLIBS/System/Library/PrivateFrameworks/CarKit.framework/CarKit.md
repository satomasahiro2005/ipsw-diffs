## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x613c8` | `0x619d0` | **`+0x608`** |
| `__TEXT.__gcc_except_tab` | `0x984` | `0x9e8` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x10230` | `0x10290` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x62b4` | `0x62fc` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x6aa6` | `0x6ae6` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x36c0` | `0x36e0` | **`+0x20`** |
| `__TEXT.__const` | `0x548` | `0x558` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5a8d` | `0x5a9d` | **`+0x10`** |
| `__DATA.__data` | `0x1194` | `0x11a0` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x17c` | `0x188` | **`+0xc`** |
| `__AUTH.__data` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x724` | `0x72c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1bd8` | `0x1bd0` | **`-0x8`** |

### Other Changes

```diff

-792.0.0.0.0
+794.0.0.0.0

-  Functions: 3032
-  Symbols:   4725
-  CStrings:  1417
+  Functions: 3038
+  Symbols:   4734
+  CStrings:  1418
Symbols:
+ -[CARSession initWithFigEndpoint:sessionStatusOptions:nightModeProvider:]
+ -[CARSession nightModeProvider]
+ -[CARSession setNightModeProvider:]
+ -[CARSessionStatus initForCarPlayShellWithNightModeProvider:]
+ -[CARSessionStatus initWithOptions:nightModeProvider:]
+ -[CARSessionStatus nightModeProvider]
+ -[CARSessionStatus setNightModeProvider:]
+ GCC_except_table155
+ GCC_except_table179
+ GCC_except_table185
+ GCC_except_table213
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ _AFIsLinwoodEnabledAndWasEverAvailable$delayInitStub
+ _OBJC_IVAR_$_CARSession._nightModeProvider
+ _OBJC_IVAR_$_CARSessionStatus._nightModeProvider
+ ___54-[CARSessionStatus initWithOptions:nightModeProvider:]_block_invoke
+ ___54-[CARSessionStatus initWithOptions:nightModeProvider:]_block_invoke_2
+ ___73-[CARSession initWithFigEndpoint:sessionStatusOptions:nightModeProvider:]_block_invoke
+ ___73-[CARSession initWithFigEndpoint:sessionStatusOptions:nightModeProvider:]_block_invoke_2
+ _symbolic _____ySSSbG s18_DictionaryStorageC
- -[CARSession initWithFigEndpoint:sessionStatusOptions:]
- GCC_except_table152
- GCC_except_table175
- GCC_except_table181
- GCC_except_table207
- _AFIsLinwoodEnabledAndAvailable
- _AFIsLinwoodEnabledAndAvailable$delayInitStub
- ___36-[CARSessionStatus initWithOptions:]_block_invoke
- ___36-[CARSessionStatus initWithOptions:]_block_invoke_2
- ___55-[CARSession initWithFigEndpoint:sessionStatusOptions:]_block_invoke
- ___55-[CARSession initWithFigEndpoint:sessionStatusOptions:]_block_invoke_2
CStrings:
+ "Linwood not enabled or was never available, hiding Campo from CarPlay"
+ "[DDPNightMode] screen %{public}@ nightMode=%d"
- "Linwood not enabled and available, hiding Campo from CarPlay"
```
