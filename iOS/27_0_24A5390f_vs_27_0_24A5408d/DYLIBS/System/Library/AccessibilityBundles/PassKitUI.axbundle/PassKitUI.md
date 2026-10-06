## PassKitUI

> `/System/Library/AccessibilityBundles/PassKitUI.axbundle/PassKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16a7c` | `0x17400` | **`+0x984`** |
| `__AUTH_CONST.__objc_const` | `0x8a18` | `0x8c58` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0x5b20` | `0x5ce0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x45bf` | `0x4757` | **`+0x198`** |
| `__AUTH.__objc_data` | `0x550` | `0x690` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x2f4c` | `0x3044` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x938` | `0x978` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x790` | `0x7b0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xc30` | `0xc50` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x240` | `0x248` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 845
-  Symbols:   2306
-  CStrings:  779
+  Functions: 863
+  Symbols:   2345
+  CStrings:  793
Symbols:
+ +[PKMessageExtensionMessageBubbleViewAccessibility _accessibilityPerformValidations:]
+ +[PKMessageExtensionMessageBubbleViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKMessageExtensionMessageBubbleViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[PKSystemImageCellAccessibility _accessibilityPerformValidations:]
+ +[PKSystemImageCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKSystemImageCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PKMessageExtensionMessageBubbleViewAccessibility accessibilityActivate]
+ -[PKMessageExtensionMessageBubbleViewAccessibility accessibilityHint]
+ -[PKMessageExtensionMessageBubbleViewAccessibility accessibilityLabel]
+ -[PKMessageExtensionMessageBubbleViewAccessibility accessibilityTraits]
+ -[PKMessageExtensionMessageBubbleViewAccessibility isAccessibilityElement]
+ -[PKPassFieldViewAccessibility deleteButtonTappedInShadowView:]
+ -[PKSystemImageCellAccessibility accessibilityLabel]
+ -[PKSystemImageCellAccessibility accessibilityPath]
+ -[PKSystemImageCellAccessibility accessibilityTraits]
+ -[PKSystemImageCellAccessibility configureWithImageName:isSelected:foregroundColor:backgroundColor:]
+ -[PKSystemImageCellAccessibility isAccessibilityElement]
+ GCC_except_table533
+ GCC_except_table536
+ GCC_except_table540
+ GCC_except_table606
+ GCC_except_table608
+ GCC_except_table637
+ GCC_except_table671
+ GCC_except_table693
+ GCC_except_table698
+ GCC_except_table709
+ GCC_except_table747
+ GCC_except_table803
+ _OBJC_CLASS_$_PKMessageExtensionMessageBubbleViewAccessibility
+ _OBJC_CLASS_$_PKSystemImageCellAccessibility
+ _OBJC_CLASS_$_UIViewController
+ _OBJC_CLASS_$___PKMessageExtensionMessageBubbleViewAccessibility_super
+ _OBJC_CLASS_$___PKSystemImageCellAccessibility_super
+ _OBJC_METACLASS_$_PKMessageExtensionMessageBubbleViewAccessibility
+ _OBJC_METACLASS_$_PKSystemImageCellAccessibility
+ _OBJC_METACLASS_$___PKMessageExtensionMessageBubbleViewAccessibility_super
+ _OBJC_METACLASS_$___PKSystemImageCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_PKMessageExtensionMessageBubbleViewAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_PKSystemImageCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PKMessageExtensionMessageBubbleViewAccessibility
+ __OBJC_$_INSTANCE_METHODS_PKSystemImageCellAccessibility
+ __OBJC_CLASS_RO_$_PKMessageExtensionMessageBubbleViewAccessibility
+ __OBJC_CLASS_RO_$_PKSystemImageCellAccessibility
+ __OBJC_CLASS_RO_$___PKMessageExtensionMessageBubbleViewAccessibility_super
+ __OBJC_CLASS_RO_$___PKSystemImageCellAccessibility_super
+ __OBJC_METACLASS_RO_$_PKMessageExtensionMessageBubbleViewAccessibility
+ __OBJC_METACLASS_RO_$_PKSystemImageCellAccessibility
+ __OBJC_METACLASS_RO_$___PKMessageExtensionMessageBubbleViewAccessibility_super
+ __OBJC_METACLASS_RO_$___PKSystemImageCellAccessibility_super
+ ___73-[PKMessageExtensionMessageBubbleViewAccessibility accessibilityActivate]_block_invoke
- GCC_except_table524
- GCC_except_table527
- GCC_except_table531
- GCC_except_table597
- GCC_except_table599
- GCC_except_table628
- GCC_except_table662
- GCC_except_table684
- GCC_except_table689
- GCC_except_table700
- GCC_except_table729
- GCC_except_table785
CStrings:
+ "PKAXSymbolSelected"
+ "PKMessageExtensionMessageBubbleView"
+ "PKMessageExtensionMessageBubbleViewAccessibility"
+ "PKMessageExtensionMessageBubbleViewController"
+ "PKSystemImageCell"
+ "PKSystemImageCellAccessibility"
+ "_buttonLabel"
+ "_leftTitleLabel"
+ "_rightTitleLabel"
+ "_viewControllerForAncestor"
+ "configureWithImageName:isSelected:foregroundColor:backgroundColor:"
+ "deleteButtonTappedInShadowView:"
+ "didTapMessage"
+ "messages.pass.add.hint"
```
