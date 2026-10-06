## ESDaemonSupport

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/ESDaemonSupport.framework/ESDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20d28` | `0x20f5c` | **`+0x234`** |
| `__TEXT.__gcc_except_tab` | `0x578` | `0x620` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x678` | `0x6c8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1258` | `0x1270` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x680` | `0x698` | **`+0x18`** |
| `__TEXT.__cstring` | `0x10e8` | `0x10fe` | **`+0x16`** |
| `__TEXT.__const` | `0xb8` | `0xc0` | **`+0x8`** |

### Other Changes

```diff

-2076.0.0.0.0
+2078.0.0.0.0

-  Functions: 580
-  Symbols:   1296
-  CStrings:  334
+  Functions: 582
+  Symbols:   1301
+  CStrings:  335
Symbols:
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table45
+ GCC_except_table68
+ ___39-[ESDAgentManager _clearOrphanedStores]_block_invoke
+ ___DAPerformNotesOrphanCleanup_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e5_v8?0ls40l8s32l8
+ ___block_descriptor_48_e8_32s40r_e21_v16?0"NoteContext"8ls32l8r40l8
- GCC_except_table36
- GCC_except_table44
- GCC_except_table67
Functions:
~ -[ESDAgentManager _clearOrphanedStores] : 2344 -> 2132
+ ___39-[ESDAgentManager _clearOrphanedStores]_block_invoke
+ ___DAPerformNotesOrphanCleanup_block_invoke
CStrings:
+ "v16@?0@\"NoteContext\"8"
```
