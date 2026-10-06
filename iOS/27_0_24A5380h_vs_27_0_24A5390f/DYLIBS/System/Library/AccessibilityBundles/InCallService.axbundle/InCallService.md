## InCallService

> `/System/Library/AccessibilityBundles/InCallService.axbundle/InCallService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d40` | `0x4d0c` | **`-0x34`** |
| `__DATA_CONST.__const` | `0x228` | `0x200` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1540` | `0x1560` | **`+0x20`** |
| `__TEXT.__cstring` | `0xf25` | `0xf33` | **`+0xe`** |
| `__DATA_CONST.__objc_selrefs` | `0x518` | `0x520` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x268` | `0x260` | **`-0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Symbols:   532
-  CStrings:  187
+  Symbols:   531
+  CStrings:  188
Symbols:
- ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
Functions:
~ +[PHSOSViewControllerAccessibility _accessibilityPerformValidations:] : 424 -> 416
~ -[PHSOSViewControllerAccessibility accessibilityPerformEscape] : 192 -> 152
~ ___62-[PHSOSViewControllerAccessibility accessibilityPerformEscape]_block_invoke : 12 -> 8
CStrings:
+ "buttonPressed"
```
