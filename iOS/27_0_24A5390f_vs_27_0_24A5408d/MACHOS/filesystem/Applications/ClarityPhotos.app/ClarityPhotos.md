## ClarityPhotos

> `/Applications/ClarityPhotos.app/ClarityPhotos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12d34` | `0x12ce0` | **`-0x54`** |
| `__DATA.__data` | `0xc08` | `0xc00` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x430` | `0x428` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x518` | `0x510` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-165.0.0.0.0
+168.0.0.0.0

-  Functions: 453
-  Symbols:   657
+  Functions: 452
+  Symbols:   656
Symbols:
+ _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAWP
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAMc
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVN
Functions:
~ sub_1000144f0 : 84 -> 96
- sub_100014544
```
