## Translate

> `/System/Library/AccessibilityBundles/Translate.axbundle/Translate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1590` | `0x17bc` | **`+0x22c`** |
| `__AUTH_CONST.__cfstring` | `0x700` | `0x740` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xb0` | `0xd8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x5b0` | `0x5d0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x90` | `0xa8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2fc` | `0x314` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 58
-  Symbols:   220
-  CStrings:  67
+  Functions: 61
+  Symbols:   229
+  CStrings:  69
Symbols:
+ -[LanguageAwareTextViewAccessibility _accessibilityLoadAccessibilityInformation]
+ -[LanguageAwareTextViewAccessibility accessibilityPlaceholderValue]
+ _OBJC_CLASS_$_UITextView
+ _OBJC_CLASS_$_UIView
+ ___80-[LanguageAwareTextViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
+ ___block_descriptor_40_e8_32s_e12_B24?08^B16ls32l8
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_enumerationMutation
CStrings:
+ "placeholder"
+ "placeholderTextView"
```
