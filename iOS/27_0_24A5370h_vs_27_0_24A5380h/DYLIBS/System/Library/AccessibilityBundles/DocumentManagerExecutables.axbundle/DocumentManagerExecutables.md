## DocumentManagerExecutables

> `/System/Library/AccessibilityBundles/DocumentManagerExecutables.axbundle/DocumentManagerExecutables`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xcd0` | `0xf0` | **`-0xbe0`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0xe10` | **`+0xb40`** |
| `__TEXT.__text` | `0x5d34` | `0x5684` | **`-0x6b0`** |
| `__AUTH_CONST.__objc_const` | `0x2500` | `0x23e0` | **`-0x120`** |
| `__TEXT.__cstring` | `0x127b` | `0x1218` | **`-0x63`** |
| `__AUTH_CONST.__cfstring` | `0x16e0` | `0x1680` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0xf8c` | `0xf2c` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0x148` | `0x108` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x2a8` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x180` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x120` | `0x128` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 192
-  Symbols:   586
-  CStrings:  207
+  Functions: 183
+  Symbols:   569
+  CStrings:  204
Symbols:
+ -[DOCItemCollectionOutlineCellAccessibility _accessibilityIsFolder]
+ _OBJC_CLASS_$_NSAttributedString
- +[DOCItemCollectionListCellAccessibility _accessibilityPerformValidations:]
- +[DOCItemCollectionListCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[DOCItemCollectionListCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[DOCItemCollectionListCellAccessibility _accessibilityIsFolder]
- -[DOCItemCollectionListCellAccessibility _axAttrTitle]
- -[DOCItemCollectionListCellAccessibility accessibilityLabel]
- -[DOCItemCollectionListCellAccessibility accessibilityUserInputLabels]
- GCC_except_table174
- _OBJC_CLASS_$_DOCItemCollectionListCellAccessibility
- _OBJC_CLASS_$___DOCItemCollectionListCellAccessibility_super
- _OBJC_METACLASS_$_DOCItemCollectionListCellAccessibility
- _OBJC_METACLASS_$___DOCItemCollectionListCellAccessibility_super
- __OBJC_$_CLASS_METHODS_DOCItemCollectionListCellAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_DOCItemCollectionListCellAccessibility
- __OBJC_CLASS_RO_$_DOCItemCollectionListCellAccessibility
- __OBJC_CLASS_RO_$___DOCItemCollectionListCellAccessibility_super
- __OBJC_METACLASS_RO_$_DOCItemCollectionListCellAccessibility
- __OBJC_METACLASS_RO_$___DOCItemCollectionListCellAccessibility_super
- ___60-[DOCItemCollectionListCellAccessibility accessibilityLabel]_block_invoke
CStrings:
+ "DOCPickerFilenameViewAccessibility"
+ "accessibilityTitleString"
+ "node"
- "DOCItemCollectionListCellAccessibility"
- "DocumentManagerExecutables.DOCItemCollectionListCell"
- "accessibilityDateLabel"
- "accessibilitySizeLabel"
- "accessibilityTagView"
- "item"
```
