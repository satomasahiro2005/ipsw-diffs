## AppStore

> `/System/Library/AccessibilityBundles/AppStore.axbundle/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe50` | `0xb9dc` | **`-0x474`** |
| `__AUTH_CONST.__objc_const` | `0x7a10` | `0x76b0` | **`-0x360`** |
| `__DATA_DIRTY.__objc_data` | `0x4010` | `0x3e30` | **`-0x1e0`** |
| `__TEXT.__cstring` | `0x39aa` | `0x386d` | **`-0x13d`** |
| `__TEXT.__objc_methlist` | `0x282c` | `0x2704` | **`-0x128`** |
| `__AUTH_CONST.__cfstring` | `0x3ac0` | `0x39c0` | **`-0x100`** |
| `__DATA_CONST.__objc_classlist` | `0x6c8` | `0x698` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x190` | `0x168` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x6c8` | `0x6a8` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x538` | `0x520` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x210` | `0x200` | **`-0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 674
-  Symbols:   1885
-  CStrings:  518
+  Functions: 654
+  Symbols:   1834
+  CStrings:  508
Symbols:
+ GCC_except_table159
+ GCC_except_table175
+ GCC_except_table257
+ GCC_except_table597
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
- GCC_except_table179
- GCC_except_table195
- GCC_except_table277
- GCC_except_table617
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
- "AppStore.AccountActionSectionFooterView"
- "AppStore.AccountDetailCollectionViewCell"
- "AppStore.AnnotationCollectionViewCell"
- "AppStore.EditorialVideoView"
- "AppStore.TodayCardEditorialVideoView"
- "EditorialVideoView"
- "TodayCardEditorialVideoView"
- "accessibilityLinkLabel"
- "accessibilityTitleLabel, accessibilitySummaryLabel"
- "detailLabel"
```
