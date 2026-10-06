## Pegasus

> `/System/Library/AccessibilityBundles/Pegasus.axbundle/Pegasus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f80` | `0x1fa4` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x6d9` | `0x6de` | **`+0x5`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  CStrings:  90
+  CStrings:  91
Functions:
~ -[PGPictureInPictureViewControllerAccessibility _accessibilityLoadAccessibilityInformation] : 100 -> 136
CStrings:
+ "view"
```
