## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f2e4` | `0x1f380` | **`+0x9c`** |
| `__TEXT.__objc_methlist` | `0x1c04` | `0x1c14` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1868` | `0x1870` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8a8` | `0x8b0` | **`+0x8`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 739
-  Symbols:   1469
+  Functions: 740
+  Symbols:   1470
Symbols:
+ -[AXUIDisplayManager _addContentViewController:toWindow:withUserInteractionEnabled:forService:context:completion:]
+ -[AXUIDisplayManager _sceneIsAttachable:]
+ GCC_except_table417
+ GCC_except_table419
+ GCC_except_table436
+ ___114-[AXUIDisplayManager _addContentViewController:toWindow:withUserInteractionEnabled:forService:context:completion:]_block_invoke
- -[AXUIDisplayManager _addContentViewController:toWindow:forService:context:completion:]
- GCC_except_table416
- GCC_except_table418
- GCC_except_table435
- ___87-[AXUIDisplayManager _addContentViewController:toWindow:forService:context:completion:]_block_invoke
```
