## PhotosUIFramework

> `/System/Library/AccessibilityBundles/PhotosUIFramework.axbundle/PhotosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x144c8` | `0x1474c` | **`+0x284`** |
| `__AUTH_CONST.__objc_const` | `0x4e10` | `0x5050` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0x4e00` | `0x4f60` | **`+0x160`** |
| `__AUTH.__objc_data` | `0x550` | `0x690` | **`+0x140`** |
| `__TEXT.__cstring` | `0x3a16` | `0x3b3f` | **`+0x129`** |
| `__TEXT.__objc_methlist` | `0x211c` | `0x21ac` | **`+0x90`** |
| `__DATA_CONST.__objc_classlist` | `0x400` | `0x420` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7c0` | `0x7d8` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x248` | `0x250` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb0` | `0xeb8` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 664
-  Symbols:   1571
-  CStrings:  666
+  Functions: 672
+  Symbols:   1600
+  CStrings:  677
Symbols:
+ +[PUPhotoEditMenuButtonAccessibility _accessibilityPerformValidations:]
+ +[PUPhotoEditMenuButtonAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PUPhotoEditMenuButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[UIContextMenuCellContentViewAccessibility _accessibilityPerformValidations:]
+ +[UIContextMenuCellContentViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[UIContextMenuCellContentViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PUPhotoEditMenuButtonAccessibility accessibilityTraits]
+ -[UIContextMenuCellContentViewAccessibility accessibilityLabel]
+ -[UIContextMenuCellContentViewAccessibility accessibilityTraits]
+ GCC_except_table132
+ GCC_except_table168
+ GCC_except_table172
+ GCC_except_table227
+ GCC_except_table239
+ GCC_except_table334
+ GCC_except_table36
+ GCC_except_table384
+ GCC_except_table403
+ GCC_except_table424
+ GCC_except_table43
+ GCC_except_table448
+ GCC_except_table45
+ GCC_except_table479
+ GCC_except_table511
+ GCC_except_table515
+ GCC_except_table518
+ GCC_except_table571
+ GCC_except_table575
+ GCC_except_table656
+ GCC_except_table66
+ GCC_except_table69
+ _OBJC_CLASS_$_PUPhotoEditMenuButtonAccessibility
+ _OBJC_CLASS_$_UIContextMenuCellContentViewAccessibility
+ _OBJC_CLASS_$___PUPhotoEditMenuButtonAccessibility_super
+ _OBJC_CLASS_$___UIContextMenuCellContentViewAccessibility_super
+ _OBJC_METACLASS_$_PUPhotoEditMenuButtonAccessibility
+ _OBJC_METACLASS_$_UIContextMenuCellContentViewAccessibility
+ _OBJC_METACLASS_$___PUPhotoEditMenuButtonAccessibility_super
+ _OBJC_METACLASS_$___UIContextMenuCellContentViewAccessibility_super
+ _UIAccessibilityTraitPopupButton
+ __OBJC_$_CLASS_METHODS_PUPhotoEditMenuButtonAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_UIContextMenuCellContentViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PUPhotoEditMenuButtonAccessibility
+ __OBJC_$_INSTANCE_METHODS_UIContextMenuCellContentViewAccessibility
+ __OBJC_CLASS_RO_$_PUPhotoEditMenuButtonAccessibility
+ __OBJC_CLASS_RO_$_UIContextMenuCellContentViewAccessibility
+ __OBJC_CLASS_RO_$___PUPhotoEditMenuButtonAccessibility_super
+ __OBJC_CLASS_RO_$___UIContextMenuCellContentViewAccessibility_super
+ __OBJC_METACLASS_RO_$_PUPhotoEditMenuButtonAccessibility
+ __OBJC_METACLASS_RO_$_UIContextMenuCellContentViewAccessibility
+ __OBJC_METACLASS_RO_$___PUPhotoEditMenuButtonAccessibility_super
+ __OBJC_METACLASS_RO_$___UIContextMenuCellContentViewAccessibility_super
- -[PUOneUpBarsControllerAccessibility _axLoadGridButtonAccessibility:]
- GCC_except_table127
- GCC_except_table163
- GCC_except_table167
- GCC_except_table222
- GCC_except_table234
- GCC_except_table31
- GCC_except_table326
- GCC_except_table38
- GCC_except_table380
- GCC_except_table399
- GCC_except_table40
- GCC_except_table416
- GCC_except_table440
- GCC_except_table471
- GCC_except_table503
- GCC_except_table507
- GCC_except_table510
- GCC_except_table563
- GCC_except_table567
- GCC_except_table61
- GCC_except_table64
- GCC_except_table648
CStrings:
+ "PUPhotoEditMenuButton"
+ "PUPhotoEditMenuButtonAccessibility"
+ "UIContextMenuCellContentViewAccessibility"
+ "_UIContextMenuCellContentView"
+ "_iconImageView"
+ "context.menu.cell.large.grid"
+ "context.menu.cell.mixed.grid"
+ "context.menu.cell.small.grid"
+ "controlState"
+ "rectangle.grid.3x1.fill"
+ "square.grid.2x2.fill"
+ "square.grid.3x3.fill"
- "photo.browse"
```
