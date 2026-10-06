## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12dc8c` | `0x12dd30` | **`+0xa4`** |
| `__AUTH_CONST.__objc_const` | `0x25060` | `0x25030` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0xe9dc` | `0xe9f4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x70e0` | `0x70f0` | **`+0x10`** |
| `__TEXT.__const` | `0x88a` | `0x89a` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x8b24` | `0x8b34` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5948` | `0x5958` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x10d8` | `0x10d0` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x6220` | `0x6228` | **`+0x8`** |
| `__TEXT.__cstring` | `0x14ea2` | `0x14ea3` | **`+0x1`** |

### Other Changes

```diff

-4838.0.125.0.0
+4838.40.53.502.1

-  Functions: 7467
-  Symbols:   11218
+  Functions: 7469
+  Symbols:   11221
Symbols:
+ -[FPProviderDomain spotlightIndexName]
+ -[FPProviderDomainChangesReceiver _t_setCachedProviderDomainsByID:]
+ GCC_except_table99
+ _FPSpotlightIndexNamePrefix
+ _fp_bundleRecord.kFPBundleRecordAssociatedObjectKey
+ _fpfs_is_seed_build.is_seed_build
- _OBJC_IVAR_$_FPXPCAutomaticErrorProxy._retainCounter
- _OBJC_IVAR_$_FPXPCAutomaticErrorProxy._retainSelfWhileMessageIsPending
- _kFPBundleRecordAssociatedObjectKey
Functions:
~ -[FPXPCAutomaticErrorProxy .cxx_destruct] : 140 -> 128
~ -[FPXPCAutomaticErrorProxy _requestWillBegin:requestID:] : 180 -> 116
~ -[FPXPCAutomaticErrorProxy _requestDidFinish:requestDidFinishBlock:] : 144 -> 28
~ -[FPSpotlightIndexer initWithDomain:log:supportURL:dropIndexDelegate:] : 428 -> 252
- ___58-[FPSpotlightIndexer _indexOneBatchWithCompletionHandler:]_block_invoke.84
+ -[FPProviderDomainChangesReceiver _t_setCachedProviderDomainsByID:]
+ ___58-[FPSpotlightIndexer _indexOneBatchWithCompletionHandler:]_block_invoke.81
~ _fpfs_is_seed_build : 52 -> 56
~ ___fpfs_is_seed_build_block_invoke : 4 -> 16
+ -[FPProviderDomain spotlightIndexName]
~ -[NSXPCConnection(FPAdditions) fp_bundleRecord] : 172 -> 272
CStrings:
+ "4838.40.53.502.1"
+ "com.apple.FileProvider/"
- "4838.0.125"
- "com.apple.FileProvider/%@"
```
