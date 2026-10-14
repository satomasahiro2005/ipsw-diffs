## QuickLook

> `/System/Library/Frameworks/QuickLook.framework/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xddecc` | `0xde310` | **`+0x444`** |
| `__DATA_CONST.__objc_selrefs` | `0x74f8` | `0x7520` | **`+0x28`** |
| `__DATA.__data` | `0x3484` | `0x34a4` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb8d4` | `0xb8f4` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xff0` | `0x1008` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4720` | `0x4738` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x11bb8` | `0x11bc0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1760` | `0x1764` | **`+0x4`** |

### Other Changes

```diff

-1034.1.4.0.0
+1034.1.5.100.0

-  Functions: 5748
-  Symbols:   7556
+  Functions: 5754
+  Symbols:   7559
Symbols:
+ -[QLPreviewController itemStore:canShowDocumentMenuForItem:]
+ -[QLPreviewController(Overlay) _containsCenteredButtonInButtons:]
+ GCC_except_table100
+ GCC_except_table103
+ GCC_except_table108
+ GCC_except_table113
+ GCC_except_table24
+ GCC_except_table66
+ GCC_except_table75
+ GCC_except_table81
- GCC_except_table102
- GCC_except_table106
- GCC_except_table112
- GCC_except_table116
- GCC_except_table29
- GCC_except_table78
- GCC_except_table99
```
