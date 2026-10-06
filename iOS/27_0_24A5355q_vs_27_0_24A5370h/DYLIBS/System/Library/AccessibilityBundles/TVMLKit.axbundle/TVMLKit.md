## TVMLKit

> `/System/Library/AccessibilityBundles/TVMLKit.axbundle/TVMLKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x4770` | `0x4650` | **`-0x120`** |
| `__AUTH.__objc_data` | `0x960` | `0x8c0` | **`-0xa0`** |
| `__TEXT.__text` | `0x8854` | `0x87f4` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x1518` | `0x14d0` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x2a00` | `0x29e0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1d6e` | `0x1d54` | **`-0x1a`** |
| `__DATA_CONST.__objc_classlist` | `0x3f8` | `0x3e8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x608` | `0x600` | **`-0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 367
-  Symbols:   1135
-  CStrings:  358
+  Functions: 363
+  Symbols:   1121
+  CStrings:  357
Symbols:
+ GCC_except_table265
+ GCC_except_table267
- +[_TVCarouselCollectionViewAccessibility _accessibilityPerformValidations:]
- +[_TVCarouselCollectionViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[_TVCarouselCollectionViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[_TVCarouselCollectionViewAccessibility _accessibilityRepresentsInfiniteCollection]
- GCC_except_table269
- GCC_except_table271
- _OBJC_CLASS_$__TVCarouselCollectionViewAccessibility
- _OBJC_CLASS_$____TVCarouselCollectionViewAccessibility_super
- _OBJC_METACLASS_$__TVCarouselCollectionViewAccessibility
- _OBJC_METACLASS_$____TVCarouselCollectionViewAccessibility_super
- __OBJC_$_CLASS_METHODS__TVCarouselCollectionViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS__TVCarouselCollectionViewAccessibility
- __OBJC_CLASS_RO_$__TVCarouselCollectionViewAccessibility
- __OBJC_CLASS_RO_$____TVCarouselCollectionViewAccessibility_super
- __OBJC_METACLASS_RO_$__TVCarouselCollectionViewAccessibility
- __OBJC_METACLASS_RO_$____TVCarouselCollectionViewAccessibility_super
CStrings:
- "_TVCarouselCollectionView"
```
