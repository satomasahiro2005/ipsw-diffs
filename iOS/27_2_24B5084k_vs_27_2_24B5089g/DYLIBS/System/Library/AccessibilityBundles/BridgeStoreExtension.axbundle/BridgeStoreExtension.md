## BridgeStoreExtension

> `/System/Library/AccessibilityBundles/BridgeStoreExtension.axbundle/BridgeStoreExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x3900` | `0x38e0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3ce3` | `0x3cc9` | **`-0x1a`** |
| `__TEXT.__text` | `0xaf24` | `0xaf10` | **`-0x14`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  CStrings:  501
+  CStrings:  500
Functions:
~ ___48+[AXAppStore3Glue accessibilityInitializeBundle]_block_invoke_3 : 1992 -> 1972
CStrings:
- "SearchButtonAccessibility"
```
