## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/NotesShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x359330` | `0x3590dc` | **`-0x254`** |
| `__AUTH.__objc_data` | `0x2e00` | `0x2d60` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x49c8` | `0x4a68` | **`+0xa0`** |
| `__DATA.__bss` | `0x102b0` | `0x10230` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x29d0` | `0x2a40` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0xcd38` | `0xcd08` | **`-0x30`** |
| `__DATA.__data` | `0x4bc4` | `0x4ba4` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x1c98` | `0x1cb8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2158` | `0x2148` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0xf1a0` | `0xf194` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2ac0` | `0x2ab8` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x18564` | `0x1855c` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xf2b8` | `0xf2b0` | **`-0x8`** |

### Other Changes

```diff

-3001.40.8.100.1
+3001.40.9.100.1

-  Functions: 18723
-  Symbols:   17857
+  Functions: 18722
+  Symbols:   17852
Symbols:
+ GCC_except_table159
- -[ICNoteContext startIndexingWithCoreSpotlightDelegateForDescription:coordinator:]
- GCC_except_table149
- GCC_except_table160
- _ICUseCoreDataCoreSpotlightIntegration
- _OBJC_CLASS_$_ICCDCSIReindexer
- _OBJC_CLASS_$_ICCoreDataCoreSpotlightDelegate
Functions:
~ ___36-[ICNoteContext persistentContainer]_block_invoke : 1584 -> 1348
- -[ICNoteContext startIndexingWithCoreSpotlightDelegateForDescription:coordinator:]
~ -[ICNoteContext startSearchIndexerChangeObservingSynchronously] : 172 -> 144
~ -[ICNoteContext finishPendingSearchIndexingSynchronously] : 200 -> 192
~ ___92-[ICNoteContext createAdditionalPersistentStoresWithAccountIdentifiers:persistentContainer:]_block_invoke : 1816 -> 1764
~ +[ICReindexer reindexer] : 80 -> 12
~ -[ICModernSearchIndexerDataSource contextWillSave:] : 604 -> 576
```
