## MobileStoreUI

> `/System/Library/PrivateFrameworks/MobileStoreUI.framework/MobileStoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e625c` | `0x2e62cc` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x139e8` | `0x13a18` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1eb8` | `0x1ed0` | **`+0x18`** |

### Other Changes

```diff

-1203.1.1.0.0
+1203.1.2.0.0

-  Symbols:   33317
+  Symbols:   33320
Symbols:
+ _OBJC_CLASS_$_UIBackgroundConfiguration
+ _OBJC_CLASS_$_UIContentUnavailableConfiguration
+ _OBJC_CLASS_$_UIContentUnavailableView
Functions:
~ -[SUUIAttributedStringView initWithFrame:] : 88 -> 140
~ -[SUUIIPadDownloadsViewController _reload] : 484 -> 536
~ +[SUUIHorizontalLockupView _attributedStringForLabel:context:] : 480 -> 500
~ +[SUUISectionHeaderView _attributedStringForButton:context:] : 368 -> 360
~ +[SUUISectionHeaderView _attributedStringForLabel:context:] : 564 -> 508
~ -[SUUIIPhoneDownloadsViewController _reload] : 480 -> 532
```
