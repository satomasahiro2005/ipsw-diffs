## SearchUI

> `/System/Library/AccessibilityBundles/SearchUI.axbundle/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ec4` | `0xa064` | **`+0x1a0`** |
| `__AUTH_CONST.__cfstring` | `0x2420` | `0x2440` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1a1d` | `0x1a39` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x550` | `0x568` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xf54` | `0xf64` | **`+0x10`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 319
-  Symbols:   846
-  CStrings:  306
+  Functions: 321
+  Symbols:   848
+  CStrings:  307
Symbols:
+ -[SearchUITableViewCellAccessibility _axSwiftUIAccessibilityElements]
+ ___69-[SearchUITableViewCellAccessibility _axSwiftUIAccessibilityElements]_block_invoke
CStrings:
+ "AXIsQueryingSwiftUIElements"
```
