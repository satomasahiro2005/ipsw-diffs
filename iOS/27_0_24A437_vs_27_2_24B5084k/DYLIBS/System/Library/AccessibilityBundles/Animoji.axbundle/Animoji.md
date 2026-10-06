## Animoji

> `/System/Library/AccessibilityBundles/Animoji.axbundle/Animoji`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24cc` | `0x2680` | **`+0x1b4`** |
| `__AUTH_CONST.__objc_const` | `0x700` | `0x5e0` | **`-0x120`** |
| `__AUTH.__objc_data` | `0x3c0` | `0x320` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x9b2` | `0x94c` | **`-0x66`** |
| `__AUTH_CONST.__cfstring` | `0xda0` | `0xd60` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e8` | `0x320` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x50` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x28` | `0x20` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x354` | `0x35c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x150` | `0x148` | **`-0x8`** |
| `__DATA.__bss` | `0xc` | `0xe` | **`+0x2`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 71
-  Symbols:   221
-  CStrings:  127
+  Functions: 74
+  Symbols:   220
+  CStrings:  124
Symbols:
+ -[PuppetCollectionViewCellAccessibility _accessibilityPuppetCollectionViewController:]
+ -[PuppetCollectionViewCellAccessibility _axRecordDescription]
+ -[PuppetCollectionViewCellAccessibility _axRecord]
+ -[PuppetCollectionViewCellAccessibility _setAXRecord:]
+ -[PuppetCollectionViewCellAccessibility _setAXRecordDescription:]
+ -[PuppetCollectionViewCellAccessibility accessibilityLabel]
+ -[PuppetCollectionViewCellAccessibility accessibilityTraits]
+ -[PuppetCollectionViewCellAccessibility isAccessibilityElement]
+ GCC_except_table12
+ GCC_except_table40
+ GCC_except_table65
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_UICollectionView
+ ___59-[PuppetCollectionViewCellAccessibility accessibilityLabel]_block_invoke
+ ___PuppetCollectionViewCellAccessibility___axRecord
+ ___PuppetCollectionViewCellAccessibility___axRecordDescription
+ _objc_autorelease
+ _objc_retain_x19
- +[PuppetCollectionViewControllerAccessibility _accessibilityPerformValidations:]
- +[PuppetCollectionViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[PuppetCollectionViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[PuppetCollectionViewCellAccessibility displaySelection:]
- -[PuppetCollectionViewControllerAccessibility collectionView:cellForItemAtIndexPath:]
- GCC_except_table15
- GCC_except_table37
- GCC_except_table62
- _OBJC_CLASS_$_PuppetCollectionViewControllerAccessibility
- _OBJC_CLASS_$___PuppetCollectionViewControllerAccessibility_super
- _OBJC_METACLASS_$_PuppetCollectionViewControllerAccessibility
- _OBJC_METACLASS_$___PuppetCollectionViewControllerAccessibility_super
- __OBJC_$_CLASS_METHODS_PuppetCollectionViewControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_PuppetCollectionViewControllerAccessibility
- __OBJC_CLASS_RO_$_PuppetCollectionViewControllerAccessibility
- __OBJC_CLASS_RO_$___PuppetCollectionViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$_PuppetCollectionViewControllerAccessibility
- __OBJC_METACLASS_RO_$___PuppetCollectionViewControllerAccessibility_super
- ___85-[PuppetCollectionViewControllerAccessibility collectionView:cellForItemAtIndexPath:]_block_invoke
CStrings:
+ "UICollectionViewCell"
+ "selectedRowIndex"
- "PuppetCollectionViewControllerAccessibility"
- "UICollectionView"
- "_puppetCollectionView"
- "collectionView:cellForItemAtIndexPath:"
- "displaySelection:"
```
