## AppleServiceToolkit

> `/System/Library/PrivateFrameworks/AppleServiceToolkit.framework/AppleServiceToolkit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x2d40` | `0x2d00` | **`-0x40`** |
| `__TEXT.__cstring` | `0x2c0d` | `0x2be4` | **`-0x29`** |
| `__TEXT.__gcc_except_tab` | `0x10c0` | `0x10e8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x63a0` | `0x63c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xb88` | `0xb78` | **`-0x10`** |
| `__DATA.__bss` | `0x148` | `0x140` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xc98` | `0xca0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x3a8` | **`+0x4`** |
| `__TEXT.__text` | `0x2c98c` | `0x2c990` | **`+0x4`** |

### Other Changes

```diff

-234.0.2.0.0
+234.40.3.0.0

-  Symbols:   2360
-  CStrings:  675
+  Symbols:   2358
+  CStrings:  673
Symbols:
+ _OBJC_IVAR_$_ASTEnvironment._assetURL
- _ASTAssetURL
- _ASTTimberLorrySessionKey
- _kASTIdentityAliasDictionaryTimberLorryKey
Functions:
~ -[ASTIdentityAlias init] : 352 -> 216
~ -[ASTEnvironment assetURL] : 12 -> 84
~ -[ASTEnvironment setAssetURL:] : 372 -> 428
~ -[ASTEnvironment .cxx_destruct] : 80 -> 92
CStrings:
- "TimberLorrySession"
- "isTimberLorryTestSession"
```
