## PhoneKit

> `/System/Library/PrivateFrameworks/PhoneKit.framework/PhoneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19b80` | `0x19d04` | **`+0x184`** |
| `__DATA.__bss` | `0x1d0` | `0x1a0` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0xb8` | `0xe0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x10bc` | `0x10d4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x658` | `0x670` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x160` | `0x174` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x11b0` | `0x11c0` | **`+0x10`** |
| `__DATA.__data` | `0x3a8` | `0x3a0` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-143.100.11.2.1
+145.100.7.2.1

-  Functions: 521
-  Symbols:   1039
+  Functions: 524
+  Symbols:   1043
Symbols:
+ -[PKRecentsController localizedSubtitleExcludingCallNotesForRecentCall:]
+ -[PKRecentsController localizedSubtitleForRecentCall:includeCallNotes:]
+ GCC_except_table133
+ ___72-[PKRecentsController localizedSubtitleExcludingCallNotesForRecentCall:]_block_invoke
```
