## ShareSheet

> `/System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc6e3c` | `0xc7544` | **`+0x708`** |
| `__TEXT.__oslogstring` | `0x7110` | `0x7195` | **`+0x85`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c10` | `0x8c30` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2044` | `0x202c` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x1130c` | `0x11314` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3528` | `0x3530` | **`+0x8`** |

### Other Changes

```diff

-2124.10.2.2.2
+2126.10.4.0.0

-  Functions: 5894
-  Symbols:   10256
-  CStrings:  1611
+  Functions: 5897
+  Symbols:   10258
+  CStrings:  1613
Symbols:
+ -[UIMessageActivity _insertCompositionContentForText:]
+ GCC_except_table183
+ GCC_except_table186
+ GCC_except_table196
+ __UIActivityItemsContainMixedContent
- GCC_except_table182
- GCC_except_table185
- GCC_except_table194
CStrings:
+ "Disabled shelf staging because activity items contains mixed content."
+ "Preparing activityItems - canInterweaveMessageContent=%{BOOL}d"
```
