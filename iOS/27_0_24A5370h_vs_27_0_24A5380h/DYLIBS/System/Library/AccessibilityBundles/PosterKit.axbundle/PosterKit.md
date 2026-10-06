## PosterKit

> `/System/Library/AccessibilityBundles/PosterKit.axbundle/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x1310` | `0x1590` | **`+0x280`** |
| `__AUTH.__objc_data` | `0x280` | `0xa0` | **`-0x1e0`** |
| `__TEXT.__text` | `0x72c0` | `0x7448` | **`+0x188`** |
| `__AUTH_CONST.__objc_const` | `0x26d0` | `0x27f0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x1c28` | `0x1d39` | **`+0x111`** |
| `__AUTH_CONST.__cfstring` | `0x2260` | `0x2340` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0xc8c` | `0xcec` | **`+0x60`** |
| `__DATA_CONST.__objc_classlist` | `0x228` | `0x238` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x530` | `0x538` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x320` | `0x328` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 242
-  Symbols:   728
-  CStrings:  292
+  Functions: 248
+  Symbols:   745
+  CStrings:  299
Symbols:
+ +[PRContentStylePickerControlAccessibility _accessibilityPerformValidations:]
+ +[PRContentStylePickerControlAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PRContentStylePickerControlAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PRContentStylePickerControlAccessibility accessibilityHint]
+ -[PRContentStylePickerControlAccessibility accessibilityLabel]
+ -[PRContentStylePickerControlAccessibility accessibilityValue]
+ GCC_except_table107
+ GCC_except_table148
+ GCC_except_table150
+ GCC_except_table82
+ GCC_except_table84
+ _OBJC_CLASS_$_PRContentStylePickerControlAccessibility
+ _OBJC_CLASS_$_UIButton
+ _OBJC_CLASS_$___PRContentStylePickerControlAccessibility_super
+ _OBJC_METACLASS_$_PRContentStylePickerControlAccessibility
+ _OBJC_METACLASS_$___PRContentStylePickerControlAccessibility_super
+ __OBJC_$_CLASS_METHODS_PRContentStylePickerControlAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PRContentStylePickerControlAccessibility
+ __OBJC_CLASS_RO_$_PRContentStylePickerControlAccessibility
+ __OBJC_CLASS_RO_$___PRContentStylePickerControlAccessibility_super
+ __OBJC_METACLASS_RO_$_PRContentStylePickerControlAccessibility
+ __OBJC_METACLASS_RO_$___PRContentStylePickerControlAccessibility_super
- GCC_except_table101
- GCC_except_table142
- GCC_except_table144
- GCC_except_table76
- GCC_except_table78
CStrings:
+ "PRContentStylePickerControl"
+ "PRContentStylePickerControlAccessibility"
+ "content.style.picker.control.hint.to.compact"
+ "content.style.picker.control.hint.to.full"
+ "content.style.picker.control.label"
+ "content.style.picker.control.value.large"
+ "content.style.picker.control.value.small"
```
