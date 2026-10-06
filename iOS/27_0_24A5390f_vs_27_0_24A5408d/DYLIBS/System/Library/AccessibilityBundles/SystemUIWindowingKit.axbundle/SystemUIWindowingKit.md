## SystemUIWindowingKit

> `/System/Library/AccessibilityBundles/SystemUIWindowingKit.axbundle/SystemUIWindowingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e8` | `0x82c` | **`+0x44`** |
| `__TEXT.__cstring` | `0x4b6` | `0x4f8` | **`+0x42`** |
| `__AUTH_CONST.__cfstring` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xe0` | `0xf0` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  CStrings:  50
+  CStrings:  51
Functions:
~ -[SystemUIWindowingKitUIContextMenuCellContentViewAccessibility accessibilityLabel] : 632 -> 700
CStrings:
+ "com.apple.springboardhome.application-shortcut-item.open-in-split"
```
