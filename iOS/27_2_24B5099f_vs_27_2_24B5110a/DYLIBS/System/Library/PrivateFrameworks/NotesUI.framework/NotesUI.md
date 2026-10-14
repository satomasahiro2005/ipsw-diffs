## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/NotesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c1094` | `0x2c1828` | **`+0x794`** |
| `__DATA.__data` | `0x57fc` | `0x587c` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x9e98` | `0x9f00` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x2ef8` | `0x2f40` | **`+0x48`** |
| `__TEXT.__const` | `0xa3a4` | `0xa3c4` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x172b0` | `0x172c8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x10100` | `0x10110` | **`+0x10`** |
| `__AUTH.__data` | `0x1c50` | `0x1c58` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x4ac8` | `0x4ad0` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0xa505` | `0xa502` | **`-0x3`** |

### Other Changes

```diff

-3001.40.11.102.1
+3001.42.1.0.0

-  Functions: 15104
-  Symbols:   16007
+  Functions: 15127
+  Symbols:   16012
Symbols:
+ -[ICTTTextStorage didOpenUndoGroup:]
+ -[ICTTTextStorage withUndoCoalescingBreakingDisabled:]
+ GCC_except_table83
+ GCC_except_table96
+ _NSUndoManagerDidOpenUndoGroupNotification
+ ___29-[ICTTTextStorage endEditing]_block_invoke
+ ___48-[ICTableCellMergeableStringDelegate endEditing]_block_invoke
- GCC_except_table71
- GCC_except_table93
```
