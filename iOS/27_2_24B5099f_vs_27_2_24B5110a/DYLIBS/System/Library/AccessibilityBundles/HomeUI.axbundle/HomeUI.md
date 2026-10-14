## HomeUI

> `/System/Library/AccessibilityBundles/HomeUI.axbundle/HomeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4529` | `0x44fe` | **`-0x2b`** |
| `__TEXT.__text` | `0x1382c` | `0x13850` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0xb08` | `0xb10` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  CStrings:  738
+  CStrings:  736
Functions:
~ +[HULiveMosaicCameraCellAccessibility _accessibilityPerformValidations:] : 116 -> 152
CStrings:
- "Optional<HFItem>"
- "Optional<HMCameraProfile>"
```
