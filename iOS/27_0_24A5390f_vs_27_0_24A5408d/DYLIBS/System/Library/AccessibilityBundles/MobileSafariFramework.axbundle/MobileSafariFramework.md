## MobileSafariFramework

> `/System/Library/AccessibilityBundles/MobileSafariFramework.axbundle/MobileSafariFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x3880` | `0x38e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2c7b` | `0x2cd3` | **`+0x58`** |
| `__TEXT.__text` | `0xca8c` | `0xcad8` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x768` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x558` | `0x550` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 426
-  Symbols:   1148
-  CStrings:  527
+  Functions: 428
+  Symbols:   1150
+  CStrings:  530
Symbols:
+ -[MainButtonAccessibility accessibilityLabel]
+ GCC_except_table126
+ GCC_except_table131
+ GCC_except_table152
+ GCC_except_table232
+ GCC_except_table233
+ GCC_except_table265
+ GCC_except_table309
+ GCC_except_table314
+ GCC_except_table318
+ GCC_except_table340
+ GCC_except_table386
+ GCC_except_table411
+ GCC_except_table412
+ GCC_except_table95
+ ___48-[SFStepperAccessibility accessibilityDecrement]_block_invoke
+ ___48-[SFStepperAccessibility accessibilityIncrement]_block_invoke
- -[SFStepperAccessibility _accessibilityLoadAccessibilityInformation]
- GCC_except_table124
- GCC_except_table129
- GCC_except_table150
- GCC_except_table226
- GCC_except_table229
- GCC_except_table263
- GCC_except_table307
- GCC_except_table312
- GCC_except_table316
- GCC_except_table338
- GCC_except_table384
- GCC_except_table409
- GCC_except_table410
- GCC_except_table94
CStrings:
+ "Decrement"
+ "Increment"
+ "SFBarButtonGroupContainerAccessibility"
+ "decrementButtonActionHandler"
+ "incrementButtonActionHandler"
- "leadingButton"
- "trailingButton"
```
