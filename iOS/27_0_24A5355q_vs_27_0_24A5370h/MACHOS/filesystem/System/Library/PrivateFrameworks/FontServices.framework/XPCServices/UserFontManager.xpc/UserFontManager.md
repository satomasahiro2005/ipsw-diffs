## UserFontManager

> `/System/Library/PrivateFrameworks/FontServices.framework/XPCServices/UserFontManager.xpc/UserFontManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x881c` | `0x8b3c` | **`+0x320`** |
| `__TEXT.__cstring` | `0xafb` | `0xb85` | **`+0x8a`** |
| `__DATA_CONST.__cfstring` | `0xc40` | `0xc80` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1100` | `0x1140` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x120c` | `0x1229` | **`+0x1d`** |
| `__TEXT.__gcc_except_tab` | `0x1b0` | `0x19c` | **`-0x14`** |
| `__DATA.__objc_selrefs` | `0x608` | `0x618` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x110` | `0x120` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x200` | `0x208` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-167.0.0.0.0
+168.0.0.0.0

-  Functions: 122
-  Symbols:   132
-  CStrings:  371
+  Functions: 124
+  Symbols:   135
+  CStrings:  375
Symbols:
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSXPCConnection
+ _ValueHasExpectedClassOrNil
CStrings:
+ "currentConnection"
+ "installFonts received malformed fontsInfo; dropping the connection."
+ "invalidate"
+ "uninstallFonts received malformed fontsInfo; dropping the connection."
```
