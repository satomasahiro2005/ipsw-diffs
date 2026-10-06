## Arcade

> `/System/Library/AccessibilityBundles/Arcade.axbundle/Arcade`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x3880` | `0x3860` | **`-0x20`** |
| `__TEXT.__cstring` | `0x35be` | `0x35a4` | **`-0x1a`** |
| `__TEXT.__text` | `0xa3d8` | `0xa3c4` | **`-0x14`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  CStrings:  489
+  CStrings:  488
Functions:
~ ___48+[AXAppStore3Glue accessibilityInitializeBundle]_block_invoke_3 : 1952 -> 1932
CStrings:
- "SearchButtonAccessibility"
```
