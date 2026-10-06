## WorkflowUIServices

> `/System/Library/AccessibilityBundles/WorkflowUIServices.axbundle/WorkflowUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3144` | `0x33a8` | **`+0x264`** |
| `__AUTH_CONST.__cfstring` | `0x8c0` | `0x900` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x228` | `0x25c` | **`+0x34`** |
| `__TEXT.__cstring` | `0x725` | `0x753` | **`+0x2e`** |
| `__DATA_CONST.__const` | `0x2b8` | `0x2e0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x250` | `0x268` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x270` | `0x278` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 71
-  Symbols:   260
-  CStrings:  89
+  Functions: 73
+  Symbols:   263
+  CStrings:  93
Symbols:
+ -[WFSlotTemplateViewAccessibility _accessibilityExpandedStringForAttributedString:]
+ GCC_except_table61
+ ___83-[WFSlotTemplateViewAccessibility _accessibilityExpandedStringForAttributedString:]_block_invoke
+ ___84-[WFIntelligencePromptFieldAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_4
+ ___block_descriptor_40_e8_32s_e45_v40?0"NSTextAttachment"8{_NSRange=QQ}16^B32ls32l8
+ ___block_descriptor_40_e8_32w_e15_"NSString"8?0lw32l8
+ _objc_retain_x23
- GCC_except_table58
- ___53-[WFSlotTemplateViewAccessibility accessibilityLabel]_block_invoke_3
- ___block_descriptor_40_e8_32r_e45_v40?0"NSTextAttachment"8{_NSRange=QQ}16^B32lr32l8
- _objc_retain_x22
CStrings:
+ "@\"NSString\"8@?0"
+ "NSString"
+ "checkmark"
+ "detachedButtonSymbolName"
+ "prompt.field.attachment"
+ "prompt.field.done"
+ "variableName"
- "WFVariable"
- "nameIncludingPropertyName"
- "token.nameIncludingPropertyName"
```
