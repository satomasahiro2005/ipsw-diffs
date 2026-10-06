## ASMessagesProvider

> `/System/Library/AccessibilityBundles/ASMessagesProvider.axbundle/ASMessagesProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb45c` | `0xae40` | **`-0x61c`** |
| `__AUTH_CONST.__objc_const` | `0x77d0` | `0x7470` | **`-0x360`** |
| `__AUTH.__objc_data` | `0x4290` | `0x40b0` | **`-0x1e0`** |
| `__TEXT.__cstring` | `0x3cbd` | `0x3b32` | **`-0x18b`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x3820` | **`-0x140`** |
| `__TEXT.__objc_methlist` | `0x2724` | `0x25fc` | **`-0x128`** |
| `__TEXT.__unwind_info` | `0x670` | `0x638` | **`-0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x6a8` | `0x678` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x190` | `0x168` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x510` | `0x4f8` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x200` | `0x1f0` | **`-0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 654
-  Symbols:   1842
-  CStrings:  505
+  Functions: 634
+  Symbols:   1791
+  CStrings:  495
Symbols:
+ GCC_except_table123
+ GCC_except_table138
+ GCC_except_table221
+ GCC_except_table611
- +[AccountActionSectionFooterViewAccessibility _accessibilityPerformValidations:]
- +[AccountActionSectionFooterViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[AccountActionSectionFooterViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[AccountDetailCollectionViewCellAccessibility _accessibilityPerformValidations:]
- +[AccountDetailCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[AccountDetailCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[AnnotationCollectionViewCellAccessibility _accessibilityPerformValidations:]
- +[AnnotationCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[AnnotationCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[AccountActionSectionFooterViewAccessibility accessibilityLabel]
- -[AccountActionSectionFooterViewAccessibility isAccessibilityElement]
- -[AccountDetailCollectionViewCellAccessibility accessibilityLabel]
- -[AccountDetailCollectionViewCellAccessibility accessibilityTraits]
- -[AccountDetailCollectionViewCellAccessibility isAccessibilityElement]
- -[AnnotationCollectionViewCellAccessibility _accessibilityPerformLinkAction:]
- -[AnnotationCollectionViewCellAccessibility _axLinkLabel]
- -[AnnotationCollectionViewCellAccessibility accessibilityCustomActions]
- -[AnnotationCollectionViewCellAccessibility accessibilityLabel]
- -[AnnotationCollectionViewCellAccessibility isAccessibilityElement]
- GCC_except_table143
- GCC_except_table158
- GCC_except_table241
- GCC_except_table631
- _OBJC_CLASS_$_AccountActionSectionFooterViewAccessibility
- _OBJC_CLASS_$_AccountDetailCollectionViewCellAccessibility
- _OBJC_CLASS_$_AnnotationCollectionViewCellAccessibility
- _OBJC_CLASS_$___AccountActionSectionFooterViewAccessibility_super
- _OBJC_CLASS_$___AccountDetailCollectionViewCellAccessibility_super
- _OBJC_CLASS_$___AnnotationCollectionViewCellAccessibility_super
- _OBJC_METACLASS_$_AccountActionSectionFooterViewAccessibility
- _OBJC_METACLASS_$_AccountDetailCollectionViewCellAccessibility
- _OBJC_METACLASS_$_AnnotationCollectionViewCellAccessibility
- _OBJC_METACLASS_$___AccountActionSectionFooterViewAccessibility_super
- _OBJC_METACLASS_$___AccountDetailCollectionViewCellAccessibility_super
- _OBJC_METACLASS_$___AnnotationCollectionViewCellAccessibility_super
- __OBJC_$_CLASS_METHODS_AccountActionSectionFooterViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_AccountDetailCollectionViewCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_AnnotationCollectionViewCellAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_AccountActionSectionFooterViewAccessibility
- __OBJC_$_INSTANCE_METHODS_AccountDetailCollectionViewCellAccessibility
- __OBJC_$_INSTANCE_METHODS_AnnotationCollectionViewCellAccessibility
- __OBJC_CLASS_RO_$_AccountActionSectionFooterViewAccessibility
- __OBJC_CLASS_RO_$_AccountDetailCollectionViewCellAccessibility
- __OBJC_CLASS_RO_$_AnnotationCollectionViewCellAccessibility
- __OBJC_CLASS_RO_$___AccountActionSectionFooterViewAccessibility_super
- __OBJC_CLASS_RO_$___AccountDetailCollectionViewCellAccessibility_super
- __OBJC_CLASS_RO_$___AnnotationCollectionViewCellAccessibility_super
- __OBJC_METACLASS_RO_$_AccountActionSectionFooterViewAccessibility
- __OBJC_METACLASS_RO_$_AccountDetailCollectionViewCellAccessibility
- __OBJC_METACLASS_RO_$_AnnotationCollectionViewCellAccessibility
- __OBJC_METACLASS_RO_$___AccountActionSectionFooterViewAccessibility_super
- __OBJC_METACLASS_RO_$___AccountDetailCollectionViewCellAccessibility_super
- __OBJC_METACLASS_RO_$___AnnotationCollectionViewCellAccessibility_super
- ___77-[AnnotationCollectionViewCellAccessibility _accessibilityPerformLinkAction:]_block_invoke
- ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
CStrings:
- "ASMessagesProvider.AccountActionSectionFooterView"
- "ASMessagesProvider.AccountDetailCollectionViewCell"
- "ASMessagesProvider.AnnotationCollectionViewCell"
- "AccountActionSectionFooterViewAccessibility"
- "AccountDetailCollectionViewCellAccessibility"
- "AnnotationCollectionViewCellAccessibility"
- "accessibilityLinkLabel"
- "accessibilityLinkLabelTapped"
- "accessibilityTitleLabel, accessibilitySummaryLabel"
- "detailLabel"
```
