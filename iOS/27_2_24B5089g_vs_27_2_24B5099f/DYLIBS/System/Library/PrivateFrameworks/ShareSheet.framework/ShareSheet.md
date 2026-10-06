## ShareSheet

> `/System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc8aa8` | `0xc8d54` | **`+0x2ac`** |
| `__TEXT.__oslogstring` | `0x726d` | `0x72aa` | **`+0x3d`** |
| `__TEXT.__objc_methlist` | `0x1141c` | `0x11434` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8cf0` | `0x8d00` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x35a8` | `0x35b0` | **`+0x8`** |

### Other Changes

```diff

-2131.20.71.0.0
+2131.21.21.0.0

-  Functions: 5931
-  Symbols:   10303
-  CStrings:  1622
+  Functions: 5934
+  Symbols:   10308
+  CStrings:  1623
Symbols:
+ -[SHSheetContentLayoutProvider _createHorizontalLayoutSectionWithContext:iconWidth:sectionHeight:scrollable:labelHeightCalculationBlock:]
+ -[UIActivityContentViewController _topActionsMaximumCountFromCurrentWidth]
+ -[UIActivityContentViewController _updateTopActionsMaximumCountIfNeeded]
+ GCC_except_table104
+ GCC_except_table119
+ GCC_except_table129
+ GCC_except_table132
+ GCC_except_table51
- -[SHSheetContentLayoutProvider _createHorizontalLayoutSectionWithContext:iconWidth:sectionHeight:labelHeightCalculationBlock:]
- GCC_except_table102
- GCC_except_table130
CStrings:
+ "refusing to decode disallowed activity class name:%{public}@"
```
