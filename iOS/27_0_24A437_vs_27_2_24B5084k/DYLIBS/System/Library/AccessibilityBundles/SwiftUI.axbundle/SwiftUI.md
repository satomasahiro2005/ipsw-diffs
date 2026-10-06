## SwiftUI

> `/System/Library/AccessibilityBundles/SwiftUI.axbundle/SwiftUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e94` | `0x3010` | **`+0x17c`** |
| `__TEXT.__cstring` | `0x4d3` | `0x4fb` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x560` | `0x580` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xec` | `0xfc` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x208` | `0x218` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4f0` | `0x4f8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 103
-  Symbols:   307
-  CStrings:  53
+  Functions: 105
+  Symbols:   310
+  CStrings:  54
Symbols:
+ -[AccessibilityNodeAccessibility _accessibilityShouldSpeakExplorerElementsAfterFocus]
+ GCC_except_table60
+ GCC_except_table70
+ GCC_except_table76
+ ___85-[AccessibilityNodeAccessibility _accessibilityShouldSpeakExplorerElementsAfterFocus]_block_invoke
- GCC_except_table62
- GCC_except_table74
CStrings:
+ "AXShouldSpeakExplorerElementsAfterFocus"
```
