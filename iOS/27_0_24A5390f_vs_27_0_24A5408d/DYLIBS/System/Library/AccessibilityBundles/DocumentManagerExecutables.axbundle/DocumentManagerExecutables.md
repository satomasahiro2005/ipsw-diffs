## DocumentManagerExecutables

> `/System/Library/AccessibilityBundles/DocumentManagerExecutables.axbundle/DocumentManagerExecutables`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5684` | `0x5470` | **`-0x214`** |
| `__AUTH.__objc_data` | `0xf0` | `0x190` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xe10` | `0xd70` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1680` | `0x16a0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x860` | `0x878` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1218` | `0x1207` | **`-0x11`** |
| `__DATA_CONST.__objc_superrefs` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xf3c` | `0xf34` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x2a0` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  CStrings:  204
+  CStrings:  205
Symbols:
+ +[DOCFullDocumentManagerViewControllerAccessibility _accessibilityPerformValidations:]
+ +[DOCFullDocumentManagerViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[DOCFullDocumentManagerViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[DOCFullDocumentManagerViewControllerAccessibility accessibilityPerformEscape]
+ GCC_except_table100
+ GCC_except_table115
+ _OBJC_CLASS_$_DOCFullDocumentManagerViewControllerAccessibility
+ _OBJC_CLASS_$___DOCFullDocumentManagerViewControllerAccessibility_super
+ _OBJC_METACLASS_$_DOCFullDocumentManagerViewControllerAccessibility
+ _OBJC_METACLASS_$___DOCFullDocumentManagerViewControllerAccessibility_super
+ __OBJC_$_CLASS_METHODS_DOCFullDocumentManagerViewControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_DOCFullDocumentManagerViewControllerAccessibility
+ __OBJC_CLASS_RO_$_DOCFullDocumentManagerViewControllerAccessibility
+ __OBJC_CLASS_RO_$___DOCFullDocumentManagerViewControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_DOCFullDocumentManagerViewControllerAccessibility
+ __OBJC_METACLASS_RO_$___DOCFullDocumentManagerViewControllerAccessibility_super
+ ___79-[DOCFullDocumentManagerViewControllerAccessibility accessibilityPerformEscape]_block_invoke
- +[DOCItemCollectionOutlineCellAccessibility _accessibilityPerformValidations:]
- +[DOCItemCollectionOutlineCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[DOCItemCollectionOutlineCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[DOCItemCollectionOutlineCellAccessibility _accessibilityIsFolder]
- -[DOCItemCollectionOutlineCellAccessibility accessibilityLabel]
- GCC_except_table110
- GCC_except_table95
- _OBJC_CLASS_$_DOCItemCollectionOutlineCellAccessibility
- _OBJC_CLASS_$___DOCItemCollectionOutlineCellAccessibility_super
- _OBJC_METACLASS_$_DOCItemCollectionOutlineCellAccessibility
- _OBJC_METACLASS_$___DOCItemCollectionOutlineCellAccessibility_super
- __OBJC_$_CLASS_METHODS_DOCItemCollectionOutlineCellAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_DOCItemCollectionOutlineCellAccessibility
- __OBJC_CLASS_RO_$_DOCItemCollectionOutlineCellAccessibility
- __OBJC_CLASS_RO_$___DOCItemCollectionOutlineCellAccessibility_super
- __OBJC_METACLASS_RO_$_DOCItemCollectionOutlineCellAccessibility
- __OBJC_METACLASS_RO_$___DOCItemCollectionOutlineCellAccessibility_super
CStrings:
+ "DOCFullDocumentManagerViewControllerAccessibility"
+ "_canNavigateBack"
+ "_navigateBack"
- "DOCItemCollectionOutlineCellAccessibility"
- "DocumentManagerExecutables.DOCItemCollectionOutlineCell"
```
