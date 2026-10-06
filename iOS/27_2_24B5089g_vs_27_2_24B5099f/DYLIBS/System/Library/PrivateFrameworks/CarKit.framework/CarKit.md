## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__delay_helper` | `0xa4` | `—` | **`-0xa4`** |
| `__TEXT.__text` | `0x628a8` | `0x62928` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x6c86` | `0x6c26` | **`-0x60`** |
| `__TEXT.__cstring` | `0x5bbd` | `0x5b6d` | **`-0x50`** |
| `__TEXT.__delay_stubs` | `0x40` | `—` | **`-0x40`** |
| `__AUTH.__data` | `0x1b8` | `0x188` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `—` | `0x30` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x10390` | `0x10370` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xae0` | `0xad0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1c18` | `0x1c20` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x738` | `0x734` | **`-0x4`** |

### Other Changes

```diff

-807.2.0.0.0
+807.4.0.0.0

-  Symbols:   4762
-  CStrings:  1436
+  Symbols:   4757
+  CStrings:  1434
Symbols:
+ GCC_except_table122
- GCC_except_table121
- _AFIsLinwoodEnabledAndWasEverAvailable
- _AFIsLinwoodEnabledAndWasEverAvailable$delayInitStub
- _OBJC_IVAR_$_CARSession._videoPlaybackAvailable
- _dlopenHelper$AssistantServices
- _dlopenHelperFlag$AssistantServices
Functions:
~ -[CARSession videoPlaybackAvailable] : 8 -> 228
~ -[CARSession .cxx_destruct] : 176 -> 164
~ -[CRCarPlayAppPolicyEvaluator _isCampoSupported] : 304 -> 224
CStrings:
+ "SiriApp is installed"
- "/System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices"
- "Linwood not enabled or was never available, hiding Campo from CarPlay"
- "SiriApp is installed and Linwood is enabled and available"
```
