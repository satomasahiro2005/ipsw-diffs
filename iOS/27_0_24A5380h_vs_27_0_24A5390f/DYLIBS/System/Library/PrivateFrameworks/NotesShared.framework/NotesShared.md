## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/NotesShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x349430` | `0x34a028` | **`+0xbf8`** |
| `__TEXT.__oslogstring` | `0x1cbc9` | `0x1cc89` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x64c0` | `0x6510` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x182dc` | `0x18324` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x223a8` | `0x223e8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xcbc0` | `0xcbf8` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xf0a4` | `0xf0bc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf018` | `0xf030` | **`+0x18`** |
| `__DATA.__data` | `0x4a5c` | `0x4a6c` | **`+0x10`** |
| `__TEXT.__const` | `0xdb68` | `0xdb58` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x4338` | `0x4348` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2a50` | `0x2a58` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2130` | `0x2138` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd88` | `0xd8c` | **`+0x4`** |

### Other Changes

```diff

-2996.0.0.0.0
+2998.0.0.0.0

-  Functions: 18521
-  Symbols:   17697
-  CStrings:  5270
+  Functions: 18532
+  Symbols:   17713
+  CStrings:  5272
Symbols:
+ -[ICCRArray removeAllObjects]
+ -[ICCloudSyncingObject isSharedViaAccessRequests]
+ -[ICInlineAttachment cachedLinkedNoteIsPasswordProtectedAndLocked]
+ -[ICInlineAttachment linkedNoteIsPasswordProtectedAndLocked]
+ -[ICInlineAttachment linkedNote]
+ -[ICInlineAttachment setCachedLinkedNoteIsPasswordProtectedAndLocked:]
+ -[ICTTArray removeAllObjects]
+ GCC_except_table282
+ GCC_except_table294
+ GCC_except_table432
+ GCC_except_table437
+ GCC_except_table442
+ _ICInternalSettingsCloudSharingUISharingExpEnabled
+ _OBJC_IVAR_$_ICInlineAttachment._cachedLinkedNoteIsPasswordProtectedAndLocked
+ ___29-[ICCRArray removeAllObjects]_block_invoke
+ ___56-[ICCloudContext updateCloudContextStateWithCompletion:]_block_invoke_4
+ ___block_descriptor_48_e8_32bs40r_e5_v8?0ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e19_v16?0"ICCRArray"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e30_v24?0"CKRecord"8"NSError"16ls32l8s40l8s48l8
+ _symbolic _____y______GSg_ADt ScS12ContinuationV 6Speech13AnalyzerInputV
- GCC_except_table281
- GCC_except_table430
- GCC_except_table435
- ___block_descriptor_56_e8_32s40s48s_e30_v24?0"CKRecord"8"NSError"16ls32l8s40l8s48l8
CStrings:
+ "Asset file for %@ was evicted before it could be written; re-fetching from cloud: %@"
+ "Timed out waiting for user record fetch; balancing group so the update-context completion isn't stranded"
```
