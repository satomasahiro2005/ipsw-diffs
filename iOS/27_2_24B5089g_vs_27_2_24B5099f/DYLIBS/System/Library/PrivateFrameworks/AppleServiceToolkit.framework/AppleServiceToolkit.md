## AppleServiceToolkit

> `/System/Library/PrivateFrameworks/AppleServiceToolkit.framework/AppleServiceToolkit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c990` | `0x2cd88` | **`+0x3f8`** |
| `__TEXT.__gcc_except_tab` | `0x10e8` | `0x11ac` | **`+0xc4`** |
| `__AUTH_CONST.__const` | `0x2c0` | `0x280` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x63c0` | `0x6400` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xca0` | `0xcd8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x2be4` | `0x2bc2` | **`-0x22`** |
| `__DATA.__bss` | `0x140` | `0x128` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x3a8` | `0x3b0` | **`+0x8`** |

### Other Changes

```diff

-234.40.3.0.0
+234.40.4.0.0

-  Functions: 1257
+  Functions: 1256

-  CStrings:  673
+  CStrings:  672
Symbols:
+ GCC_except_table17
+ GCC_except_table21
+ _OBJC_IVAR_$_ASTEnvironment._configCode
+ _OBJC_IVAR_$_ASTEnvironment._diagsChannel
- _ASTConfigCode
- _ASTCurrentDiagsChannel
- _ASTEnvironmentSyncQueue
- ___36+[ASTEnvironment currentEnvironment]_block_invoke_2
CStrings:
- "com.apple.ASTEnvironmentSyncQueue"
```
