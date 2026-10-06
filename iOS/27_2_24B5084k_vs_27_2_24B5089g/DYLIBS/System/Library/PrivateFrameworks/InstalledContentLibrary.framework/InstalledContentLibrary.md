## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3b00` | `0xd3cb8` | **`+0x1b8`** |
| `__TEXT.__cstring` | `0x18bee` | `0x18c2e` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5eb4` | `0x5ec4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xc68` | `0xc70` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x31e0` | `0x31e8` | **`+0x8`** |

### Other Changes

```diff

-1680.40.6.502.1
+1680.40.8.0.1

-  Functions: 2510
-  Symbols:   3885
-  CStrings:  2306
+  Functions: 2511
+  Symbols:   3889
+  CStrings:  2307
Symbols:
+ -[MIMCMContainer setMcmContainer:]
+ GCC_except_table26
+ GCC_except_table37
+ _container_operation_copy_superseded
Functions:
+ -[MIMCMContainer setMcmContainer:]
~ -[MIMCMContainer supersedeExistingContainer:error:] : 8 -> 392
CStrings:
+ "-[MIMCMContainer supersedeExistingContainer:error:]"
```
