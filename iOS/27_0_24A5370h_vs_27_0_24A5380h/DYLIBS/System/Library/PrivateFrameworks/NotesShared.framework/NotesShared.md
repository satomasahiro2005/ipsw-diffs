## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/NotesShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x348ae0` | `0x349430` | **`+0x950`** |
| `__TEXT.__oslogstring` | `0x1c909` | `0x1cbc9` | **`+0x2c0`** |
| `__AUTH.__objc_data` | `0x2fe0` | `0x2d60` | **`-0x280`** |
| `__DATA_DIRTY.__objc_data` | `0x4748` | `0x49c8` | **`+0x280`** |
| `__DATA_DIRTY.__bss` | `0x2930` | `0x29d0` | **`+0xa0`** |
| `__DATA.__bss` | `0x10230` | `0x101a0` | **`-0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb80` | `0xcbc0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1829c` | `0x182dc` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xefe0` | `0xf018` | **`+0x38`** |
| `__DATA.__data` | `0x4a8c` | `0x4a5c` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0x1c58` | `0x1c88` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xf9e0` | `0xfa00` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2120` | `0x2130` | **`+0x10`** |
| `__TEXT.__cstring` | `0x19334` | `0x19344` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x223a0` | `0x223a8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xf0a8` | `0xf0a4` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x3ec` | `0x3e8` | **`-0x4`** |

### Other Changes

```diff

-2991.0.0.0.0
+2996.0.0.0.0

-  Functions: 18515
-  Symbols:   17689
-  CStrings:  5263
+  Functions: 18521
+  Symbols:   17697
+  CStrings:  5270
Symbols:
+ +[ICInlineAttachment refreshDisplayTextForParagraphLinkAttachments:reason:]
+ +[ICReindexer migrateSearchIndexVersionIfNeeded]
+ -[ICNote(SearchIndexableNote) shouldDeferIndexingInMemoryConstrainedExtension]
+ -[ICNoteContext finishPendingSearchIndexingSynchronously]
+ -[ICNoteContext startSearchIndexerChangeObservingSynchronously]
+ GCC_except_table158
+ ___57-[ICNoteContext finishPendingSearchIndexingSynchronously]_block_invoke
+ ___block_descriptor_56_e8_32s40s48r_e27_v40?08{_NSRange=QQ}16^B32ls32l8s40l8r48l8
+ _kICReindexAttachmentsOnLaunchKey
- ___block_descriptor_56_e8_32s40s48r_e27_v40?08{_NSRange=QQ}16^B32ls32l8r48l8s40l8
CStrings:
+ "No need to delete search indexing before reindexing. Updating the indexing version to expected version"
+ "Search index does not need to be upgraded although indexing version does not match. Current version = %lu, expected version = %lu. Directly updating the indexing version to expected version"
+ "Search index needs to be upgraded because indexing version does not match. Current version = %lu, expected version = %lu"
+ "allIndexableObjectIDsInReversedReindexingOrderWithContext: data source %@ skipping attachments (ICIndexingScopeExcludingAttachments)"
+ "rdar23306437-memcal: indexing note %@ charCount=%lu serializedNoteData=%lu bytes"
+ "rdar23306437-memcal: note %@ serializedNoteData=%lu bytes threshold=%lu defer=%@"
+ "reindexAttachmentsOnLaunch"
```
