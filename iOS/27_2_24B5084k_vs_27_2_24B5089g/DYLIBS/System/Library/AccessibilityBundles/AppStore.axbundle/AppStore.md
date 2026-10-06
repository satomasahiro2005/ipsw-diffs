## AppStore

> `/System/Library/AccessibilityBundles/AppStore.axbundle/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3c0` | `0x370` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x3e30` | `0x3e80` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3a40` | `0x3a20` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3927` | `0x390d` | **`-0x1a`** |
| `__TEXT.__text` | `0xba80` | `0xba6c` | **`-0x14`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  CStrings:  515
+  CStrings:  514
Functions:
~ ___48+[AXAppStore3Glue accessibilityInitializeBundle]_block_invoke_3 : 2032 -> 2012
CStrings:
- "SearchButtonAccessibility"
```
