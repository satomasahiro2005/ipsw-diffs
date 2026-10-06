## WorkflowUIServices

> `/System/Library/AccessibilityBundles/WorkflowUIServices.axbundle/WorkflowUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f7c` | `0x3144` | **`+0x1c8`** |
| `__AUTH_CONST.__cfstring` | `0x8a0` | `0x8c0` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x23c` | `0x228` | **`-0x14`** |
| `__TEXT.__cstring` | `0x714` | `0x725` | **`+0x11`** |
| `__DATA_CONST.__objc_selrefs` | `0x240` | `0x250` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e8` | `0x1f0` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 70
-  Symbols:   258
-  CStrings:  88
+  Functions: 71
+  Symbols:   260
+  CStrings:  89
Symbols:
+ -[WFIntelligencePromptFieldAccessibility accessibilityElements]
+ GCC_except_table59
+ _OBJC_CLASS_$_NSConstantArray
- GCC_except_table57
Functions:
~ +[WFIntelligencePromptFieldAccessibility _accessibilityPerformValidations:] : 236 -> 264
~ -[WFIntelligencePromptFieldAccessibility _accessibilityLoadAccessibilityInformation] : 1064 -> 1032
+ -[WFIntelligencePromptFieldAccessibility accessibilityElements]
CStrings:
+ "attachmentButton"
```
