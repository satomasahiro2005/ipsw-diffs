## PassKitUI

> `/System/Library/AccessibilityBundles/PassKitUI.axbundle/PassKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16240` | `0x16a7c` | **`+0x83c`** |
| `__AUTH_CONST.__objc_const` | `0x8478` | `0x8a18` | **`+0x5a0`** |
| `__AUTH.__objc_data` | `0x230` | `0x550` | **`+0x320`** |
| `__AUTH_CONST.__cfstring` | `0x5900` | `0x5b20` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x2d8c` | `0x2f4c` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x4417` | `0x45bf` | **`+0x1a8`** |
| `__DATA_CONST.__objc_classlist` | `0x740` | `0x790` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x8f0` | `0x938` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xbf0` | `0xc30` | **`+0x40`** |
| `__DATA_CONST.__objc_superrefs` | `0x250` | `0x270` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__const` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 817
-  Symbols:   2226
-  CStrings:  762
+  Functions: 845
+  Symbols:   2306
+  CStrings:  779
Symbols:
+ +[PKBackFieldTableCellAccessibility _accessibilityPerformValidations:]
+ +[PKBackFieldTableCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKBackFieldTableCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[PKColorButtonCollectionViewCellAccessibility _accessibilityPerformValidations:]
+ +[PKColorButtonCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKColorButtonCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[PKImageCellAccessibility _accessibilityPerformValidations:]
+ +[PKImageCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKImageCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[PKTextureButtonCollectionViewCellAccessibility _accessibilityPerformValidations:]
+ +[PKTextureButtonCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKTextureButtonCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[PKUITextFieldAccessibility _accessibilityPerformValidations:]
+ +[PKUITextFieldAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKUITextFieldAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PKBackFieldTableCellAccessibility accessibilityLabel]
+ -[PKColorButtonCollectionViewCellAccessibility accessibilityLabel]
+ -[PKColorButtonCollectionViewCellAccessibility accessibilityPath]
+ -[PKColorButtonCollectionViewCellAccessibility accessibilityTraits]
+ -[PKColorButtonCollectionViewCellAccessibility isAccessibilityElement]
+ -[PKImageCellAccessibility accessibilityLabel]
+ -[PKImageCellAccessibility accessibilityTraits]
+ -[PKImageCellAccessibility configureWithImage:label:isSelected:]
+ -[PKImageCellAccessibility isAccessibilityElement]
+ -[PKTextureButtonCollectionViewCellAccessibility accessibilityLabel]
+ -[PKTextureButtonCollectionViewCellAccessibility accessibilityTraits]
+ -[PKTextureButtonCollectionViewCellAccessibility isAccessibilityElement]
+ -[PKUITextFieldAccessibility _accessibilityHasSensitiveCursorContent]
+ GCC_except_table123
+ GCC_except_table266
+ GCC_except_table302
+ GCC_except_table323
+ GCC_except_table349
+ GCC_except_table369
+ GCC_except_table524
+ GCC_except_table527
+ GCC_except_table531
+ GCC_except_table597
+ GCC_except_table599
+ GCC_except_table628
+ GCC_except_table662
+ GCC_except_table684
+ GCC_except_table689
+ GCC_except_table700
+ GCC_except_table729
+ GCC_except_table785
+ _CGRectGetWidth
+ _OBJC_CLASS_$_PKBackFieldTableCellAccessibility
+ _OBJC_CLASS_$_PKColorButtonCollectionViewCellAccessibility
+ _OBJC_CLASS_$_PKImageCellAccessibility
+ _OBJC_CLASS_$_PKTextureButtonCollectionViewCellAccessibility
+ _OBJC_CLASS_$_PKUITextFieldAccessibility
+ _OBJC_CLASS_$_UIBezierPath
+ _OBJC_CLASS_$___PKBackFieldTableCellAccessibility_super
+ _OBJC_CLASS_$___PKColorButtonCollectionViewCellAccessibility_super
+ _OBJC_CLASS_$___PKImageCellAccessibility_super
+ _OBJC_CLASS_$___PKTextureButtonCollectionViewCellAccessibility_super
+ _OBJC_CLASS_$___PKUITextFieldAccessibility_super
+ _OBJC_METACLASS_$_PKBackFieldTableCellAccessibility
+ _OBJC_METACLASS_$_PKColorButtonCollectionViewCellAccessibility
+ _OBJC_METACLASS_$_PKImageCellAccessibility
+ _OBJC_METACLASS_$_PKTextureButtonCollectionViewCellAccessibility
+ _OBJC_METACLASS_$_PKUITextFieldAccessibility
+ _OBJC_METACLASS_$___PKBackFieldTableCellAccessibility_super
+ _OBJC_METACLASS_$___PKColorButtonCollectionViewCellAccessibility_super
+ _OBJC_METACLASS_$___PKImageCellAccessibility_super
+ _OBJC_METACLASS_$___PKTextureButtonCollectionViewCellAccessibility_super
+ _OBJC_METACLASS_$___PKUITextFieldAccessibility_super
+ __OBJC_$_CLASS_METHODS_PKBackFieldTableCellAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_PKColorButtonCollectionViewCellAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_PKImageCellAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_PKTextureButtonCollectionViewCellAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_PKUITextFieldAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PKBackFieldTableCellAccessibility
+ __OBJC_$_INSTANCE_METHODS_PKColorButtonCollectionViewCellAccessibility
+ __OBJC_$_INSTANCE_METHODS_PKImageCellAccessibility
+ __OBJC_$_INSTANCE_METHODS_PKTextureButtonCollectionViewCellAccessibility
+ __OBJC_$_INSTANCE_METHODS_PKUITextFieldAccessibility
+ __OBJC_CLASS_RO_$_PKBackFieldTableCellAccessibility
+ __OBJC_CLASS_RO_$_PKColorButtonCollectionViewCellAccessibility
+ __OBJC_CLASS_RO_$_PKImageCellAccessibility
+ __OBJC_CLASS_RO_$_PKTextureButtonCollectionViewCellAccessibility
+ __OBJC_CLASS_RO_$_PKUITextFieldAccessibility
+ __OBJC_CLASS_RO_$___PKBackFieldTableCellAccessibility_super
+ __OBJC_CLASS_RO_$___PKColorButtonCollectionViewCellAccessibility_super
+ __OBJC_CLASS_RO_$___PKImageCellAccessibility_super
+ __OBJC_CLASS_RO_$___PKTextureButtonCollectionViewCellAccessibility_super
+ __OBJC_CLASS_RO_$___PKUITextFieldAccessibility_super
+ __OBJC_METACLASS_RO_$_PKBackFieldTableCellAccessibility
+ __OBJC_METACLASS_RO_$_PKColorButtonCollectionViewCellAccessibility
+ __OBJC_METACLASS_RO_$_PKImageCellAccessibility
+ __OBJC_METACLASS_RO_$_PKTextureButtonCollectionViewCellAccessibility
+ __OBJC_METACLASS_RO_$_PKUITextFieldAccessibility
+ __OBJC_METACLASS_RO_$___PKBackFieldTableCellAccessibility_super
+ __OBJC_METACLASS_RO_$___PKColorButtonCollectionViewCellAccessibility_super
+ __OBJC_METACLASS_RO_$___PKImageCellAccessibility_super
+ __OBJC_METACLASS_RO_$___PKTextureButtonCollectionViewCellAccessibility_super
+ __OBJC_METACLASS_RO_$___PKUITextFieldAccessibility_super
- GCC_except_table119
- GCC_except_table262
- GCC_except_table294
- GCC_except_table315
- GCC_except_table341
- GCC_except_table361
- GCC_except_table496
- GCC_except_table499
- GCC_except_table503
- GCC_except_table569
- GCC_except_table571
- GCC_except_table600
- GCC_except_table634
- GCC_except_table656
- GCC_except_table661
- GCC_except_table672
- GCC_except_table701
- GCC_except_table757
CStrings:
+ "PKAXBackgroundImageSelected"
+ "PKBackFieldTableCell"
+ "PKBackFieldTableCellAccessibility"
+ "PKColorButtonCollectionViewCell"
+ "PKColorButtonCollectionViewCellAccessibility"
+ "PKImageCell"
+ "PKImageCellAccessibility"
+ "PKTextureButtonCollectionViewCell"
+ "PKTextureButtonCollectionViewCellAccessibility"
+ "PKUITextField"
+ "PKUITextFieldAccessibility"
+ "UICollectionViewCell"
+ "_titleTextView"
+ "_valueTextView"
+ "color"
+ "configureWithImage:label:isSelected:"
+ "isSelected"
```
