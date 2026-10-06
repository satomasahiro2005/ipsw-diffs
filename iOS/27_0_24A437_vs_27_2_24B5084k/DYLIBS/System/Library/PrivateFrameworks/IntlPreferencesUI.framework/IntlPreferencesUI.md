## IntlPreferencesUI

> `/System/Library/PrivateFrameworks/IntlPreferencesUI.framework/IntlPreferencesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18ffc` | `0x1912c` | **`+0x130`** |
| `__DATA_CONST.__got` | `0x448` | `0x450` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xad8` | `0xae0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-496.0.0.0.0
+498.0.0.0.0

-  Symbols:   653
-  CStrings:  122
+  Symbols:   654
+  CStrings:  121
Symbols:
+ -[IPPronounPickerViewController lastLayoutWidth]
+ -[IPPronounPickerViewController setLastLayoutWidth:]
+ _OBJC_CLASS_$_NSIndexPath
+ _OBJC_IVAR_$_IPPronounPickerViewController._lastLayoutWidth
- -[IPPronounPickerViewController setViewHasChangedSize:]
- -[IPPronounPickerViewController viewHasChangedSize]
- _OBJC_IVAR_$_IPPronounPickerViewController._viewHasChangedSize
Functions:
~ -[IPPronounPickerViewController viewDidLayoutSubviews] : 84 -> 292
~ -[IPPronounPickerViewController tableView:cellForRowAtIndexPath:] : 2192 -> 2144
~ -[IPPronounPickerViewController viewWillTransitionToSize:withTransitionCoordinator:] : 8 -> 56
~ -[IPPronounPickerViewController contentSizeCategoryDidChange:] : 4 -> 88
~ -[IPPronounPickerViewController createLanguageMenuButton] : 1996 -> 2008
CStrings:
- "#"
```
