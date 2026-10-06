## SearchUI

> `/System/Library/AccessibilityBundles/SearchUI.axbundle/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c40` | `0x9ec4` | **`+0x284`** |
| `__AUTH_CONST.__cfstring` | `0x2380` | `0x2420` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x19b3` | `0x1a1d` | **`+0x6a`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x550` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xf3c` | `0xf54` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x170` | `0x178` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x438` | `0x440` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 317
-  Symbols:   843
-  CStrings:  301
+  Functions: 319
+  Symbols:   846
+  CStrings:  306
Symbols:
+ -[SearchUIVerticalLayoutCardSectionViewAccessibility _axPhotoImageDescriptionForThumbnail:]
+ -[SearchUIVerticalLayoutCardSectionViewAccessibility _axThumbnail]
+ GCC_except_table111
+ GCC_except_table81
+ GCC_except_table92
+ _OBJC_CLASS_$_NSNull
- GCC_except_table109
- GCC_except_table79
- GCC_except_table90
CStrings:
+ "%p-_axPhotoImageDescription-%@"
+ "SearchUIPhotoAssetCache"
+ "descriptionProperties"
+ "photo.result"
+ "photoIdentifier"
```
