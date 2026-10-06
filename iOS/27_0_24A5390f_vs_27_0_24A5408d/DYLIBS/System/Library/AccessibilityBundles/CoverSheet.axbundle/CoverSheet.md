## CoverSheet

> `/System/Library/AccessibilityBundles/CoverSheet.axbundle/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d1c` | `0x5da4` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x1ee0` | `0x1f20` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x2c8` | `0x2f0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1934` | `0x195c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x480` | `0x488` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 201
-  Symbols:   575
-  CStrings:  273
+  Functions: 202
+  Symbols:   577
+  CStrings:  275
Symbols:
+ GCC_except_table108
+ GCC_except_table126
+ GCC_except_table134
+ GCC_except_table136
+ GCC_except_table160
+ GCC_except_table82
+ GCC_except_table86
+ _AXSBChargingController
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
- GCC_except_table107
- GCC_except_table124
- GCC_except_table133
- GCC_except_table135
- GCC_except_table158
- GCC_except_table81
- GCC_except_table85
Functions:
+ _AXSBChargingController
~ +[CSCoverSheetViewAccessibility _accessibilityPerformValidations:] : 1112 -> 1148
~ -[CSCoverSheetViewAccessibility _axHandleShowNotificationsAction] : 384 -> 376
~ ___65-[CSCoverSheetViewAccessibility _axHandleShowNotificationsAction]_block_invoke : 76 -> 184
~ -[CSCoverSheetViewAccessibility _accessibilityAdditionalElements] : 424 -> 400
CStrings:
+ "chargingController"
+ "didTapCountIndicator"
```
