## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4b0` | `0x25f8` | **`+0x2148`** |
| `__DATA_DIRTY.__objc_data` | `0x3cf0` | `0x1bf8` | **`-0x20f8`** |
| `__TEXT.__text` | `0x12bafc` | `0x12d0ac` | **`+0x15b0`** |
| `__AUTH_CONST.__objc_const` | `0x24e58` | `0x25008` | **`+0x1b0`** |
| `__TEXT.__objc_methlist` | `0xe8a4` | `0xe97c` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x114e0` | `0x115a0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x14d8f` | `0x14e47` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x8a54` | `0x8af8` | **`+0xa4`** |
| `__TEXT.__oslogstring` | `0xe2b3` | `0xe335` | **`+0x82`** |
| `__DATA_CONST.__objc_selrefs` | `0x7028` | `0x70a8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x6188` | `0x61f8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x58c0` | `0x5910` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xad0` | `0xb18` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x10c0` | `0x10d4` | **`+0x14`** |
| `__DATA.__bss` | `0xc20` | `0xc30` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x690` | `0x698` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x548` | `0x550` | **`+0x8`** |

### Other Changes

```diff

-4838.0.29.502.2
+4838.0.70.0.0

-  Functions: 7422
-  Symbols:   11159
-  CStrings:  4045
+  Functions: 7453
+  Symbols:   11203
+  CStrings:  4056
Symbols:
+ +[FPFINodeSession sharedSession]
+ +[NSFileManager(FPAdditionsTesting) _test_flushFINodeSession]
+ +[NSFileManager(FPAdditionsTesting) _test_setFINodeSessionIdleTimeout:]
+ -[FPFINodeSession .cxx_destruct]
+ -[FPFINodeSession enter]
+ -[FPFINodeSession flushForTesting]
+ -[FPFINodeSession init]
+ -[FPFINodeSession leave]
+ -[FPFINodeSession setIdleTimeoutForTesting:]
+ -[FPItemManager _fetchSearchableItemIdentifiersForURL:synchronously:skipURLValidation:completionHandler:]
+ -[FPItemManager fetchSearchableItemIdentifiersForURL:completionHandler:]
+ -[FPItemManager searchableItemIdentifiersForURL:error:]
+ GCC_except_table121
+ GCC_except_table136
+ GCC_except_table77
+ _FPFileLockedByFlock
+ _FPURLIsKnownCiaoLocalStorage
+ _OBJC_CLASS_$_FPFINodeSession
+ _OBJC_IVAR_$_FPFINodeSession._generation
+ _OBJC_IVAR_$_FPFINodeSession._idleTimeout
+ _OBJC_IVAR_$_FPFINodeSession._outstanding
+ _OBJC_IVAR_$_FPFINodeSession._pendingGeneration
+ _OBJC_IVAR_$_FPFINodeSession._queue
+ _OBJC_METACLASS_$_FPFINodeSession
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSFileManager_$_FPAdditionsTesting
+ __OBJC_$_CATEGORY_NSFileManager_$_FPAdditionsTesting
+ __OBJC_$_CLASS_METHODS_FPFINodeSession
+ __OBJC_$_INSTANCE_METHODS_FPFINodeSession
+ __OBJC_$_INSTANCE_METHODS_NSFileManager(FPAdditionsTesting|FPAdditions)
+ __OBJC_$_INSTANCE_VARIABLES_FPFINodeSession
+ __OBJC_CLASS_RO_$_FPFINodeSession
+ __OBJC_METACLASS_RO_$_FPFINodeSession
+ ___105-[FPItemManager _fetchSearchableItemIdentifiersForURL:synchronously:skipURLValidation:completionHandler:]_block_invoke
+ ___24-[FPFINodeSession enter]_block_invoke
+ ___24-[FPFINodeSession leave]_block_invoke
+ ___24-[FPFINodeSession leave]_block_invoke_2
+ ___32+[FPFINodeSession sharedSession]_block_invoke
+ ___34-[FPFINodeSession flushForTesting]_block_invoke
+ ___44-[FPFINodeSession setIdleTimeoutForTesting:]_block_invoke
+ ___55-[FPItemManager searchableItemIdentifiersForURL:error:]_block_invoke
+ ___block_descriptor_40_e8_32s_e60_"FIOperationReply"24?0"FIOperation"8"FIOperationError"16ls32l8
+ ___block_descriptor_48_e8_32s40r_e60_"FIOperationReply"24?0"FIOperation"8"FIOperationError"16lr40l8s32l8
+ ___block_descriptor_48_e8_i12?0i8l
+ ___block_descriptor_56_e8_32s40r48r_e33_v24?0"FIOperation"8"NSArray"16lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40r_e5_v8?0lr40l8s32l8
+ ___fpfs_get_purgeable_info_at_block_invoke
+ ___fpfs_unset_purgeable_at_block_invoke
+ _fpfs_get_purgeable_info_at
+ _fpfs_query_purgeable_bytes
+ _fpfs_unset_purgeable_at
+ _sharedSession.once
+ _sharedSession.sharedSession
- GCC_except_table131
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSFileManager_$_FPAdditions
- __OBJC_$_CATEGORY_NSFileManager_$_FPAdditions
- ___71-[NSFileManager(FPAdditions) fp_trashItemAtURL:resultingItemURL:error:]_block_invoke_2
- ___block_descriptor_40_e8_32r_e60_"FIOperationReply"24?0"FIOperation"8"FIOperationError"16lr32l8
- ___block_descriptor_48_e8_32s40r_e33_v24?0"FIOperation"8"NSArray"16lr40l8s32l8
- ___fpfs_t_unset_evictable_at_block_invoke
- _fpfs_t_unset_evictable_at
CStrings:
+ "/private/var/mobile/Containers/"
+ "/var/mobile/Containers/"
+ "4838.0.70"
+ "FIOperationReply"
+ "FileLockedByFlock"
+ "NSFileManager+FPAdditions.m"
+ "[DEBUG] Item got trashed at %@ (%@)"
+ "[DEBUG] Trashing %@ failed with %@"
+ "[DEBUG] Trashing %@ got a warning: %@"
+ "[ERROR] Couldn't get a FIMoveToTrashOperation for trashing"
+ "[ERROR] Couldn't get a FINode for trashing"
+ "com.apple.FileProvider.FINodeSession"
+ "pending close with outstanding=%d"
- "4838.0.29.502.2"
- "[WARNING] Trashing going through FP instead of DS - probably not the expectation"
```
