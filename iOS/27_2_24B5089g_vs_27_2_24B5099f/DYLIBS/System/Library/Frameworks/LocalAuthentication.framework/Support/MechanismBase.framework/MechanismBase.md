## MechanismBase

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismBase.framework/MechanismBase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a174` | `0x1a2f4` | **`+0x180`** |
| `__AUTH_CONST.__objc_dictobj` | `0x78` | `0xc8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xe60` | `0xea0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xe91` | `0xeba` | **`+0x29`** |
| `__DATA_CONST.__objc_arraydata` | `0x38` | `0x58` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x11a0` | `0x11b8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1de0` | `0x1de8` | **`+0x8`** |

### Other Changes

```diff

-2319.40.35.0.1
+2319.40.43.0.0

-  Functions: 633
-  Symbols:   1360
-  CStrings:  263
+  Functions: 634
+  Symbols:   1361
+  CStrings:  265
Symbols:
+ -[MechanismBase acceptsAutomaticFallbackAfterError:]
+ GCC_except_table58
+ GCC_except_table81
- GCC_except_table57
- GCC_except_table80
Functions:
~ -[MechanismUI finishRunWithResult:error:] : 1296 -> 1308
~ -[MechanismUI _prepareInternalInfoForRemoteController] : 512 -> 688
~ -[MechanismUI_PC finishRunWithResult:error:] : 1108 -> 1120
~ -[MechanismUI_PC extendedInternalInfoForRemoteUI] : 512 -> 688
+ -[MechanismBase acceptsAutomaticFallbackAfterError:]
CStrings:
+ "NoEarlyPasscode"
+ "com.apple.appprotectiond"
```
