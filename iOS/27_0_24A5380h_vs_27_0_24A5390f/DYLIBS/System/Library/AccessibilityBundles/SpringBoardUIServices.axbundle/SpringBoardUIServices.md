## SpringBoardUIServices

> `/System/Library/AccessibilityBundles/SpringBoardUIServices.axbundle/SpringBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a28` | `0x4ba4` | **`+0x17c`** |
| `__TEXT.__unwind_info` | `0x290` | `0x2a8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e0` | `0x4e8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb44` | `0xb4c` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 207
-  Symbols:   618
+  Functions: 208
+  Symbols:   619
Symbols:
+ -[SBPasscodeNumberPadButtonAccessibility accessibilityHint]
+ GCC_except_table108
+ GCC_except_table124
+ GCC_except_table163
+ GCC_except_table42
- GCC_except_table107
- GCC_except_table123
- GCC_except_table162
- GCC_except_table41
Functions:
~ +[SBPasscodeNumberPadButtonAccessibility _accessibilityPerformValidations:] : 4 -> 124
+ -[SBPasscodeNumberPadButtonAccessibility accessibilityHint]
~ -[SBUISimpleFixedDigitPasscodeEntryFieldAccessibility _deleteLastCharacter] : 112 -> 164
```
