## TelephonyUIFramework

> `/System/Library/AccessibilityBundles/TelephonyUIFramework.axbundle/TelephonyUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x231c` | `0x2328` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b0` | `0x2a8` | **`-0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Symbols:
+ -[TPNumberPadButtonAccessibility accessibilityValue]
+ ___52-[TPNumberPadButtonAccessibility accessibilityValue]_block_invoke
- -[TPNumberPadButtonAccessibility accessibilityHint]
- ___51-[TPNumberPadButtonAccessibility accessibilityHint]_block_invoke
Functions:
~ -[TPPhonePadAccessibility accessibilityElements] : 812 -> 804
~ -[TPPhonePadAccessibility _accessibilityScannerGroupElements] : 552 -> 572
```
