## InCallService

> `/System/Library/AccessibilityBundles/InCallService.axbundle/InCallService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d0c` | `0x4e7c` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0x1560` | `0x1580` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb8` | `0xcc` | **`+0x14`** |
| `__TEXT.__cstring` | `0xf33` | `0xf44` | **`+0x11`** |
| `__DATA_CONST.__objc_selrefs` | `0x520` | `0x528` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 176
-  Symbols:   531
-  CStrings:  188
+  Functions: 177
+  Symbols:   532
+  CStrings:  189
Symbols:
+ GCC_except_table157
+ GCC_except_table171
+ ___72-[PHSlidingViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
- GCC_except_table156
- GCC_except_table170
Functions:
~ +[PHSlidingViewAccessibility _accessibilityPerformValidations:] : 372 -> 400
~ -[PHSlidingViewAccessibility _accessibilityLoadAccessibilityInformation] : 320 -> 560
+ -[PHSlidingViewAccessibility repeatingUpdateAnimatedSliderForCountdownNumber:forModel:]
CStrings:
+ "descriptionLabel"
```
