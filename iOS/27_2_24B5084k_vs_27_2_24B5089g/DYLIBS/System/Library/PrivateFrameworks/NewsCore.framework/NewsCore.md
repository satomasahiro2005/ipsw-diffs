## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/NewsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__bss` | `0x3958` | `0x5ba8` | **`+0x2250`** |
| `__DATA.__bss` | `0x11250` | `0xf030` | **`-0x2220`** |
| `__DATA_DIRTY.__data` | `0x2410` | `0x2da0` | **`+0x990`** |
| `__AUTH.__data` | `0x9b0` | `0x360` | **`-0x650`** |
| `__DATA.__data` | `0x7090` | `0x6d00` | **`-0x390`** |
| `__TEXT.__text` | `0x3e7940` | `0x3e779c` | **`-0x1a4`** |
| `__AUTH.__objc_data` | `0x6f0` | `0x570` | **`-0x180`** |
| `__DATA_DIRTY.__objc_data` | `0x11b20` | `0x11ca0` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x79310` | `0x79390` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x34e80` | `0x34ef0` | **`+0x70`** |
| `__TEXT.__const` | `0xd648` | `0xd6a8` | **`+0x60`** |
| `__DATA.__common` | `0x190` | `0x148` | **`-0x48`** |
| `__DATA_DIRTY.__common` | `0x308` | `0x350` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x40e0` | `0x40a4` | **`-0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x14aa8` | `0x14ad8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xe698` | `0xe6a8` | **`+0x10`** |

### Other Changes

```diff

-5960.0.0.0.0
+5962.0.0.0.0

-  Functions: 24320
-  Symbols:   37533
+  Functions: 24326
+  Symbols:   37535
Symbols:
+ +[FCPrivateDataController requiresHighPrioritySync]
+ +[FCPuzzleHistory requiresHighPrioritySync]
+ -[FCPrivateDataController _qualityOfServiceForNextSync]
+ -[FCReadingHistory dislikeDatesByArticleID]
+ -[NTPBReadingHistoryItem(FCReadingHistory) dislikedAt]
+ -[NTPBReadingHistoryItem(FCReadingHistory) setDislikedAt:]
+ GCC_except_table80
+ GCC_except_table89
+ ___43-[FCReadingHistory dislikeDatesByArticleID]_block_invoke
- GCC_except_table128
- GCC_except_table84
- GCC_except_table87
- GCC_except_table91
- GCC_except_table92
- _symbolic SDyS2S_So13FCFeedContextCtG
- _symbolic _____yS2S_So13FCFeedContextCtG s18_DictionaryStorageC
```
