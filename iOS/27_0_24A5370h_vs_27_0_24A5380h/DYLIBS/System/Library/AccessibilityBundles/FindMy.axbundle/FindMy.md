## FindMy

> `/System/Library/AccessibilityBundles/FindMy.axbundle/FindMy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xbd0` | `0xab0` | **`-0x120`** |
| `__TEXT.__text` | `0x2f88` | `0x2e90` | **`-0xf8`** |
| `__AUTH.__objc_data` | `0x690` | `0x5f0` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xac0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x7de` | `0x77f` | **`-0x5f`** |
| `__TEXT.__objc_methlist` | `0x374` | `0x32c` | **`-0x48`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0x98` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xa0` | `0x98` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b0` | `0x2a8` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1a8` | `0x1a0` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 84
-  Symbols:   282
-  CStrings:  104
+  Functions: 80
+  Symbols:   266
+  CStrings:  100
Symbols:
+ GCC_except_table57
+ GCC_except_table58
+ GCC_except_table60
+ GCC_except_table70
- +[FMInitialCardControllerAccessibility _accessibilityPerformValidations:]
- +[FMInitialCardControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[FMInitialCardControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[FMInitialCardControllerAccessibility presentCard:completion:]
- GCC_except_table62
- GCC_except_table64
- GCC_except_table65
- GCC_except_table74
- _OBJC_CLASS_$_FMInitialCardControllerAccessibility
- _OBJC_CLASS_$___FMInitialCardControllerAccessibility_super
- _OBJC_METACLASS_$_FMInitialCardControllerAccessibility
- _OBJC_METACLASS_$___FMInitialCardControllerAccessibility_super
- _UIAccessibilityPostNotification
- _UIAccessibilityScreenChangedNotification
- __OBJC_$_CLASS_METHODS_FMInitialCardControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_FMInitialCardControllerAccessibility
- __OBJC_CLASS_RO_$_FMInitialCardControllerAccessibility
- __OBJC_CLASS_RO_$___FMInitialCardControllerAccessibility_super
- __OBJC_METACLASS_RO_$_FMInitialCardControllerAccessibility
- __OBJC_METACLASS_RO_$___FMInitialCardControllerAccessibility_super
CStrings:
- "@?"
- "FMInitialCardControllerAccessibility"
- "FindMy.FMInitialCardController"
- "presentCard:completion:"
```
