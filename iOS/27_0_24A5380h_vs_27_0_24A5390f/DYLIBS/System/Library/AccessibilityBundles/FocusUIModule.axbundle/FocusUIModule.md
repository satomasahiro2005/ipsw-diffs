## FocusUIModule

> `/System/Library/AccessibilityBundles/FocusUIModule.axbundle/FocusUIModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd44` | `0xd98` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x130` | `0x140` | **`+0x10`** |
| `__TEXT.__cstring` | `0x265` | `0x272` | **`+0xd`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xc8` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Symbols:   98
-  CStrings:  31
+  Symbols:   99
+  CStrings:  32
Symbols:
+ _objc_release_x23
Functions:
~ ___83-[FCCCModuleViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_4 : 124 -> 208
CStrings:
+ "focus-module"
```
