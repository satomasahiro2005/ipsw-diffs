## AirDrop

> `/System/Library/AccessibilityBundles/AirDrop.axbundle/AirDrop`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x550` | `0x588` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 18
-  Symbols:   87
+  Functions: 19
+  Symbols:   88
Symbols:
+ -[AirDropBrowserViewControllerAccessibility viewDidAppear:]
+ GCC_except_table9
- GCC_except_table8
Functions:
+ -[AirDropBrowserViewControllerAccessibility viewDidAppear:]
```
