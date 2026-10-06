## Music

> `/System/Library/AccessibilityBundles/Music.axbundle/Music`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc630` | `0xc880` | **`+0x250`** |
| `__AUTH_CONST.__objc_const` | `0x3370` | `0x3490` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x280` | `0x320` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x29de` | `0x2a39` | **`+0x5b`** |
| `__AUTH_CONST.__cfstring` | `0x3680` | `0x36c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1324` | `0x1364` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x830` | `0x860` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3f0` | `0x418` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x138` | `0x140` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 399
-  Symbols:   1042
-  CStrings:  486
+  Functions: 404
+  Symbols:   1058
+  CStrings:  489
Symbols:
+ +[ContainerDetailCollectionViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ContainerDetailCollectionViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[ContainerDetailCollectionViewAccessibility _accessibilitySortedElementsWithinWithOptions:]
+ -[ContainerDetailCollectionViewAccessibility _ax_collectionIndexPathForElement:]
+ _OBJC_CLASS_$_ContainerDetailCollectionViewAccessibility
+ _OBJC_CLASS_$___ContainerDetailCollectionViewAccessibility_super
+ _OBJC_METACLASS_$_ContainerDetailCollectionViewAccessibility
+ _OBJC_METACLASS_$___ContainerDetailCollectionViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_ContainerDetailCollectionViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_ContainerDetailCollectionViewAccessibility
+ __OBJC_CLASS_RO_$_ContainerDetailCollectionViewAccessibility
+ __OBJC_CLASS_RO_$___ContainerDetailCollectionViewAccessibility_super
+ __OBJC_METACLASS_RO_$_ContainerDetailCollectionViewAccessibility
+ __OBJC_METACLASS_RO_$___ContainerDetailCollectionViewAccessibility_super
+ ___92-[ContainerDetailCollectionViewAccessibility _accessibilitySortedElementsWithinWithOptions:]_block_invoke
+ ___block_descriptor_40_e8_32s_e11_q24?0816ls32l8
CStrings:
+ "ContainerDetailCollectionViewAccessibility"
+ "Music.ContainerDetailCollectionView"
+ "q24@?0@8@16"
```
