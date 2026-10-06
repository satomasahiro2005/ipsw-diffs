## ClarityCamera

> `/Applications/ClarityCamera.app/ClarityCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22b5c` | `0x22b08` | **`-0x54`** |
| `__TEXT.__oslogstring` | `0x61b` | `0x64b` | **`+0x30`** |
| `__DATA.__data` | `0x1320` | `0x1318` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x5f8` | `0x5f0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x9d0` | `0x9c8` | **`-0x8`** |

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
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-165.0.0.0.0
+168.0.0.0.0

-  Functions: 862
-  Symbols:   841
+  Functions: 861
+  Symbols:   840
Symbols:
+ _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAWP
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAMc
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVN
Functions:
~ sub_100024430 : 84 -> 96
- sub_100024484
CStrings:
+ "Attempted to update preview rotation angle, but no rotation coordinator was set."
- "Could not create rotation coordinator"
```
