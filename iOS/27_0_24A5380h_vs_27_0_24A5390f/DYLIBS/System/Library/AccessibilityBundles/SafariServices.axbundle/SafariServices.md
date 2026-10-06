## SafariServices

> `/System/Library/AccessibilityBundles/SafariServices.axbundle/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xff0` | `0xf50` | **`-0xa0`** |
| `__TEXT.__text` | `0x59d8` | `0x5974` | **`-0x64`** |
| `__TEXT.__cstring` | `0x18b3` | `0x18ca` | **`+0x17`** |
| `__DATA_CONST.__objc_selrefs` | `0x470` | `0x478` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x998` | `0x990` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 191
+  Functions: 190

-  CStrings:  298
+  CStrings:  297
Symbols:
+ +[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityPerformValidations:]
+ +[SFRegisterableBarButtonGroupContainerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SFRegisterableBarButtonGroupContainerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]
+ GCC_except_table170
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_SFRegisterableBarButtonGroupContainerAccessibility
+ _OBJC_CLASS_$___SFRegisterableBarButtonGroupContainerAccessibility_super
+ _OBJC_METACLASS_$_SFRegisterableBarButtonGroupContainerAccessibility
+ _OBJC_METACLASS_$___SFRegisterableBarButtonGroupContainerAccessibility_super
+ __OBJC_$_CLASS_METHODS_SFRegisterableBarButtonGroupContainerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SFRegisterableBarButtonGroupContainerAccessibility
+ __OBJC_CLASS_RO_$_SFRegisterableBarButtonGroupContainerAccessibility
+ __OBJC_CLASS_RO_$___SFRegisterableBarButtonGroupContainerAccessibility_super
+ __OBJC_METACLASS_RO_$_SFRegisterableBarButtonGroupContainerAccessibility
+ __OBJC_METACLASS_RO_$___SFRegisterableBarButtonGroupContainerAccessibility_super
+ ___96-[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- +[SFBarButtonGroupContainerAccessibility _accessibilityPerformValidations:]
- +[SFBarButtonGroupContainerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[SFBarButtonGroupContainerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[SFBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]
- -[_SFPageFormatMenuControllerAccessibility _readerTextSizeAlertItem]
- GCC_except_table171
- _OBJC_CLASS_$_SFBarButtonGroupContainerAccessibility
- _OBJC_CLASS_$___SFBarButtonGroupContainerAccessibility_super
- _OBJC_METACLASS_$_SFBarButtonGroupContainerAccessibility
- _OBJC_METACLASS_$___SFBarButtonGroupContainerAccessibility_super
- __OBJC_$_CLASS_METHODS_SFBarButtonGroupContainerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_SFBarButtonGroupContainerAccessibility
- __OBJC_CLASS_RO_$_SFBarButtonGroupContainerAccessibility
- __OBJC_CLASS_RO_$___SFBarButtonGroupContainerAccessibility_super
- __OBJC_METACLASS_RO_$_SFBarButtonGroupContainerAccessibility
- __OBJC_METACLASS_RO_$___SFBarButtonGroupContainerAccessibility_super
- ___84-[SFBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
CStrings:
+ "SFRegisterableBarButtonGroupContainer"
+ "SFRegisterableBarButtonGroupContainerAccessibility"
- "?"
- "SFBarButtonGroupContainerAccessibility"
- "_readerTextSizeAlertItem"
```
