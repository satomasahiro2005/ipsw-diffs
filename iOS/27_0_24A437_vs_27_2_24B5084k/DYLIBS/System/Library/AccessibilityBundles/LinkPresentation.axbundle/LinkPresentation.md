## LinkPresentation

> `/System/Library/AccessibilityBundles/LinkPresentation.axbundle/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d88` | `0x2e00` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0xae0` | `0xb00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6e0` | `0x6eb` | **`+0xb`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x248` | `0x250` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x288` | `0x290` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x158` | `0x160` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 59
-  Symbols:   205
-  CStrings:  104
+  Functions: 60
+  Symbols:   207
+  CStrings:  106
Symbols:
+ -[LPCollaborationFooterViewAccessibility _axIsActionable]
+ GCC_except_table21
+ GCC_except_table36
+ GCC_except_table48
+ _UIAccessibilityTraitStaticText
- GCC_except_table19
- GCC_except_table34
- GCC_except_table47
Functions:
~ +[LPCollaborationFooterViewAccessibility _accessibilityPerformValidations:] : 124 -> 152
~ -[LPCollaborationFooterViewAccessibility accessibilityTraits] : 124 -> 112
+ -[LPCollaborationFooterViewAccessibility _axIsActionable]
CStrings:
+ "@?"
+ "_action"
```
