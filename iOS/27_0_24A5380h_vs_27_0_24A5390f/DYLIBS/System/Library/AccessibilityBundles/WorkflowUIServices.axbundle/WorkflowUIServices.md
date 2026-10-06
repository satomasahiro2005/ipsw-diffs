## WorkflowUIServices

> `/System/Library/AccessibilityBundles/WorkflowUIServices.axbundle/WorkflowUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2888` | `0x2f7c` | **`+0x6f4`** |
| `__AUTH_CONST.__cfstring` | `0x760` | `0x8a0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x5ef` | `0x714` | **`+0x125`** |
| `__AUTH_CONST.__objc_const` | `0x630` | `0x750` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x1bc` | `0x23c` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x220` | `0x268` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1e8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x218` | `0x240` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x90` | `0xb0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x68` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 63
-  Symbols:   233
-  CStrings:  73
+  Functions: 70
+  Symbols:   258
+  CStrings:  88
Symbols:
+ +[WFIntelligencePromptFieldAccessibility _accessibilityPerformValidations:]
+ +[WFIntelligencePromptFieldAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[WFIntelligencePromptFieldAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[WFIntelligencePromptFieldAccessibility _accessibilityLoadAccessibilityInformation]
+ GCC_except_table57
+ GCC_except_table58
+ _CGRectZero
+ _OBJC_CLASS_$_UIButton
+ _OBJC_CLASS_$_UILabel
+ _OBJC_CLASS_$_UIView
+ _OBJC_CLASS_$_WFIntelligencePromptFieldAccessibility
+ _OBJC_CLASS_$___WFIntelligencePromptFieldAccessibility_super
+ _OBJC_METACLASS_$_WFIntelligencePromptFieldAccessibility
+ _OBJC_METACLASS_$___WFIntelligencePromptFieldAccessibility_super
+ _UIAccessibilityConvertFrameToScreenCoordinates
+ __OBJC_$_CLASS_METHODS_WFIntelligencePromptFieldAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_WFIntelligencePromptFieldAccessibility
+ __OBJC_CLASS_RO_$_WFIntelligencePromptFieldAccessibility
+ __OBJC_CLASS_RO_$___WFIntelligencePromptFieldAccessibility_super
+ __OBJC_METACLASS_RO_$_WFIntelligencePromptFieldAccessibility
+ __OBJC_METACLASS_RO_$___WFIntelligencePromptFieldAccessibility_super
+ ___84-[WFIntelligencePromptFieldAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
+ ___84-[WFIntelligencePromptFieldAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
+ ___84-[WFIntelligencePromptFieldAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_3
+ _objc_opt_respondsToSelector
CStrings:
+ "UIButton"
+ "UILabel"
+ "UIView"
+ "WFIntelligencePromptFieldAccessibility"
+ "WFIntelligencePromptTextView"
+ "WFIntelligenceSymbolView"
+ "_TtC18WorkflowUIServices25WFIntelligencePromptField"
+ "accessoryButton"
+ "detachedButton"
+ "leadingSymbolView"
+ "pillView"
+ "placeholderLabel"
+ "prompt.field.cancel"
+ "prompt.field.submit"
+ "textView"
```
