## AskPermission

> `/System/Library/PrivateFrameworks/AskPermission.framework/AskPermission`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9cf4` | `0x9e98` | **`+0x1a4`** |
| `__AUTH_CONST.__cfstring` | `0xf80` | `0xfc0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x9a0` | `0x9d8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xe44` | `0xe4c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x876` | `0x87a` | **`+0x4`** |

### Other Changes

```diff

-130.1.6.0.0
+130.1.7.2.2

-  Functions: 268
-  Symbols:   667
-  CStrings:  201
+  Functions: 269
+  Symbols:   668
+  CStrings:  203
Symbols:
+ -[NSURL(AskPermission) ap_hostIsTrustedDomain:]
Functions:
+ -[NSURL(AskPermission) ap_hostIsTrustedDomain:]
CStrings:
+ "%"
+ "."
```
