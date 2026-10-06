## AdCore

> `/System/Library/PrivateFrameworks/AdCore.framework/AdCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x5bd0` | `0x5c10` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x402c` | `0x4054` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4ca0` | `0x4cc0` | **`+0x20`** |
| `__TEXT.__text` | `0x30724` | `0x30740` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fe0` | `0x1ff8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3f36` | `0x3f41` | **`+0xb`** |
| `__TEXT.__unwind_info` | `0xc28` | `0xc30` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3e8` | `0x3ec` | **`+0x4`** |

### Other Changes

```diff

-638.0.7.0.0
+638.1.0.0.0

-  Functions: 1410
-  Symbols:   2362
-  CStrings:  652
+  Functions: 1413
+  Symbols:   2366
+  CStrings:  653
Symbols:
+ -[ADUserTargetingProperties hasPageLayout]
+ -[ADUserTargetingProperties pageLayout]
+ -[ADUserTargetingProperties setPageLayout:]
+ OBJC_IVAR_$_ADUserTargetingProperties._pageLayout
CStrings:
+ "pageLayout"
```
