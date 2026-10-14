## Setup

> `/System/Library/AccessibilityBundles/Setup.axbundle/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55b0` | `0x5704` | **`+0x154`** |
| `__AUTH_CONST.__cfstring` | `0x15a0` | `0x15c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x10ed` | `0x1108` | **`+0x1b`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a8` | `0x4c0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xa44` | `0xa4c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 190
-  Symbols:   604
-  CStrings:  197
+  Functions: 191
+  Symbols:   605
+  CStrings:  198
Symbols:
+ -[BuddyAppearanceControllerAccessibility _accessibilityLabelAccessibilityButton]
+ GCC_except_table152
+ GCC_except_table92
- GCC_except_table151
- GCC_except_table91
CStrings:
+ "showAccessibilitySettings:"
```
