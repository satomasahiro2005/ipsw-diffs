## QuickLookUICore

> `/System/Library/PrivateFrameworks/QuickLookUICore.framework/QuickLookUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xa28` | `0x960` | **`-0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x168` | `0x230` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x75f8` | `0x7628` | **`+0x30`** |
| `__DATA.__bss` | `0x1a0` | `0x170` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__TEXT.__text` | `0x213b0` | `0x213c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x20f8` | `0x2100` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x3144` | `0x314c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x3a8` | **`+0x4`** |

### Other Changes

```diff

-1029.0.0.0.0
+1032.0.0.0.0

-  Functions: 1029
-  Symbols:   2147
+  Functions: 1030
+  Symbols:   2149
Symbols:
+ -[QLItemViewController prefersArrangedAccessoryView]
+ _OBJC_IVAR_$_QLItemViewController._prefersArrangedAccessoryView
Functions:
~ -[QLFPItemFetcher _registerItemCollectionIfNeeded] : 356 -> 352
+ -[QLItemViewController setIsContentManaged:]
```
