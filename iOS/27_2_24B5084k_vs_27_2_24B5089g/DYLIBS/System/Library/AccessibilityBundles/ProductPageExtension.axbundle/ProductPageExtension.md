## ProductPageExtension

> `/System/Library/AccessibilityBundles/ProductPageExtension.axbundle/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x3900` | `0x38e0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3d36` | `0x3d1c` | **`-0x1a`** |
| `__TEXT.__text` | `0xafbc` | `0xafa8` | **`-0x14`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  CStrings:  503
+  CStrings:  502
Functions:
~ ___48+[AXAppStore3Glue accessibilityInitializeBundle]_block_invoke_3 : 1992 -> 1972
CStrings:
- "SearchButtonAccessibility"
```
