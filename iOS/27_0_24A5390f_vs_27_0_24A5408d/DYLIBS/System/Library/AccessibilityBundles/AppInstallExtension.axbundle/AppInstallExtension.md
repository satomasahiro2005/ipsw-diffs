## AppInstallExtension

> `/System/Library/AccessibilityBundles/AppInstallExtension.axbundle/AppInstallExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4c0` | `0xaea4` | **`-0x61c`** |
| `__AUTH_CONST.__objc_const` | `0x78f0` | `0x7590` | **`-0x360`** |
| `__AUTH.__objc_data` | `0x4330` | `0x4150` | **`-0x1e0`** |
| `__TEXT.__cstring` | `0x3da8` | `0x3c1a` | **`-0x18e`** |
| `__AUTH_CONST.__cfstring` | `0x39e0` | `0x38a0` | **`-0x140`** |
| `__TEXT.__objc_methlist` | `0x2784` | `0x265c` | **`-0x128`** |
| `__TEXT.__unwind_info` | `0x678` | `0x640` | **`-0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x6b8` | `0x688` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x190` | `0x168` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x510` | `0x4f8` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x208` | `0x1f8` | **`-0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 660
-  Symbols:   1858
-  CStrings:  507
+  Functions: 640
+  Symbols:   1807
+  CStrings:  497
Symbols:
+ GCC_except_table123
+ GCC_except_table138
+ GCC_except_table221
+ GCC_except_table617
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
- GCC_except_table637
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
- "AccountActionSectionFooterViewAccessibility"
- "AccountDetailCollectionViewCellAccessibility"
- "AnnotationCollectionViewCellAccessibility"
- "AppInstallExtension.AccountActionSectionFooterView"
- "AppInstallExtension.AccountDetailCollectionViewCell"
- "AppInstallExtension.AnnotationCollectionViewCell"
- "accessibilityLinkLabel"
- "accessibilityLinkLabelTapped"
- "accessibilityTitleLabel, accessibilitySummaryLabel"
- "detailLabel"
```
