## ContactsUI

> `/System/Library/AccessibilityBundles/ContactsUI.axbundle/ContactsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1e0` | `—` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x2850` | `0x2a30` | **`+0x1e0`** |
| `__TEXT.__text` | `0xcdc8` | `0xce30` | **`+0x68`** |
| `__TEXT.__cstring` | `0x295e` | `0x2982` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x33a0` | `0x33c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x18cc` | `0x18dc` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x778` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 473
-  Symbols:   1345
-  CStrings:  439
+  Functions: 474
+  Symbols:   1346
+  CStrings:  440
Symbols:
+ -[CNPhotoPickerHeaderViewAccessibility updatePhotoViewWithUpdatedIdentity:]
Functions:
~ +[CNPhotoPickerHeaderViewAccessibility _accessibilityPerformValidations:] : 468 -> 496
+ -[CNPhotoPickerHeaderViewAccessibility updatePhotoViewWithUpdatedIdentity:]
CStrings:
+ "updatePhotoViewWithUpdatedIdentity:"
```
