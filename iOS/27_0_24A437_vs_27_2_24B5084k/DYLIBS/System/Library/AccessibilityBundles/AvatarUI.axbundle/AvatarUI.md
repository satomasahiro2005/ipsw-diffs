## AvatarUI

> `/System/Library/AccessibilityBundles/AvatarUI.axbundle/AvatarUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_intobj` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__text` | `0x78e4` | `0x7904` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4f8` | `0x500` | **`+0x8`** |
| `__TEXT.__cstring` | `0x13c7` | `0x13c9` | **`+0x2`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Symbols:   616
-  CStrings:  224
+  Symbols:   617
+  CStrings:  225
Symbols:
+ _OBJC_CLASS_$_NSConstantIntegerNumber
Functions:
~ -[AVTStickerSheetControllerAccessibility _axMarkupCell:indexPath:] : 376 -> 392
~ -[AVTSelectableStickerSheetControllerAccessibility _axMarkupCell:indexPath:] : 652 -> 668
CStrings:
+ "I"
```
