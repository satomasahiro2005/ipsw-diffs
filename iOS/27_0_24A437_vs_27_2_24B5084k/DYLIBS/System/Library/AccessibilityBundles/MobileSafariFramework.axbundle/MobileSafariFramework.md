## MobileSafariFramework

> `/System/Library/AccessibilityBundles/MobileSafariFramework.axbundle/MobileSafariFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcad8` | `0xcc28` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x3e70` | `0x3f90` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x15ec` | `0x1634` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x38e0` | `0x3920` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2cd3` | `0x2cff` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x140` | `0x160` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x378` | `0x388` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x550` | `0x560` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x768` | `0x770` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 428
-  Symbols:   1150
-  CStrings:  530
+  Functions: 433
+  Symbols:   1165
+  CStrings:  532
Symbols:
+ +[SFBarButtonGroupContainerAccessibility _accessibilityPerformValidations:]
+ +[SFBarButtonGroupContainerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SFBarButtonGroupContainerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SFBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]
+ GCC_except_table100
+ GCC_except_table136
+ GCC_except_table157
+ GCC_except_table235
+ GCC_except_table236
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table270
+ GCC_except_table319
+ GCC_except_table323
+ GCC_except_table345
+ GCC_except_table391
+ GCC_except_table416
+ GCC_except_table417
+ _OBJC_CLASS_$_SFBarButtonGroupContainerAccessibility
+ _OBJC_CLASS_$___SFBarButtonGroupContainerAccessibility_super
+ _OBJC_METACLASS_$_SFBarButtonGroupContainerAccessibility
+ _OBJC_METACLASS_$___SFBarButtonGroupContainerAccessibility_super
+ __OBJC_$_CLASS_METHODS_SFBarButtonGroupContainerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SFBarButtonGroupContainerAccessibility
+ __OBJC_CLASS_RO_$_SFBarButtonGroupContainerAccessibility
+ __OBJC_CLASS_RO_$___SFBarButtonGroupContainerAccessibility_super
+ __OBJC_METACLASS_RO_$_SFBarButtonGroupContainerAccessibility
+ __OBJC_METACLASS_RO_$___SFBarButtonGroupContainerAccessibility_super
+ ___84-[SFBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- GCC_except_table126
- GCC_except_table152
- GCC_except_table228
- GCC_except_table230
- GCC_except_table231
- GCC_except_table232
- GCC_except_table265
- GCC_except_table309
- GCC_except_table318
- GCC_except_table340
- GCC_except_table386
- GCC_except_table411
- GCC_except_table412
- GCC_except_table95
CStrings:
+ "SFBarButtonGroupContainer"
+ "buttonIdentifiers"
```
