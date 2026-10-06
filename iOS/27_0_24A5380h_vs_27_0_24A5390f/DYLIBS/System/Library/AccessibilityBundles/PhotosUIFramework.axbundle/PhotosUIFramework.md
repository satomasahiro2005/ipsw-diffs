## PhotosUIFramework

> `/System/Library/AccessibilityBundles/PhotosUIFramework.axbundle/PhotosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x140dc` | `0x14224` | **`+0x148`** |
| `__TEXT.__cstring` | `0x3b37` | `0x3b65` | **`+0x2e`** |
| `__AUTH_CONST.__cfstring` | `0x4f00` | `0x4f20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7b8` | `0x7c8` | **`+0x10`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 660
-  Symbols:   1591
-  CStrings:  674
+  Functions: 661
+  Symbols:   1593
+  CStrings:  675
Symbols:
+ GCC_except_table369
+ GCC_except_table388
+ GCC_except_table409
+ GCC_except_table433
+ GCC_except_table464
+ GCC_except_table496
+ GCC_except_table500
+ GCC_except_table503
+ GCC_except_table556
+ GCC_except_table560
+ GCC_except_table645
+ ___59-[PUOneUpViewControllerAccessibility _setAccessoryVisible:]_block_invoke_2
+ _dispatch_async
- GCC_except_table368
- GCC_except_table387
- GCC_except_table408
- GCC_except_table432
- GCC_except_table463
- GCC_except_table495
- GCC_except_table499
- GCC_except_table502
- GCC_except_table555
- GCC_except_table559
- GCC_except_table644
Functions:
~ +[PUOneUpBarsControllerAccessibility _accessibilityPerformValidations:] : 456 -> 424
~ +[PUOneUpViewControllerAccessibility _accessibilityPerformValidations:] : 700 -> 728
~ -[PUOneUpViewControllerAccessibility _setAccessoryVisible:] : 156 -> 332
~ ___59-[PUOneUpViewControllerAccessibility _setAccessoryVisible:]_block_invoke : 96 -> 88
+ ___59-[PUOneUpViewControllerAccessibility _setAccessoryVisible:]_block_invoke_2
CStrings:
+ "_currentAccessoryViewController"
+ "_currentAccessoryViewController.view"
- "_handleFavoriteButton:"
```
