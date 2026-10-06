## AppInstallExtension

> `/System/Library/AccessibilityBundles/AppInstallExtension.axbundle/AppInstallExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x38e0` | `0x38c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3c64` | `0x3c4a` | **`-0x1a`** |
| `__TEXT.__text` | `0xaf08` | `0xaef4` | **`-0x14`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  CStrings:  500
+  CStrings:  499
Functions:
~ ___48+[AXAppStore3Glue accessibilityInitializeBundle]_block_invoke_3 : 1992 -> 1972
CStrings:
- "SearchButtonAccessibility"
```
