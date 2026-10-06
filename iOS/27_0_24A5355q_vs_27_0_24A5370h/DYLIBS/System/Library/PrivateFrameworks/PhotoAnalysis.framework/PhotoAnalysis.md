## PhotoAnalysis

> `/System/Library/PrivateFrameworks/PhotoAnalysis.framework/PhotoAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x283d60` | `0x28422c` | **`+0x4cc`** |
| `__TEXT.__oslogstring` | `0x15790` | `0x158ef` | **`+0x15f`** |
| `__TEXT.__cstring` | `0x105b4` | `0x10605` | **`+0x51`** |
| `__DATA_CONST.__const` | `0x1e40` | `0x1e68` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x8340` | `0x8360` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x18aac` | `0x18acc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b68` | `0x4b80` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x613c` | `0x6154` | **`+0x18`** |
| `__TEXT.__const` | `0xdb00` | `0xdaf0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2228` | `0x2230` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9900` | `0x98f8` | **`-0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 9714
-  Symbols:   6393
-  CStrings:  3205
+  Functions: 9717
+  Symbols:   6398
+  CStrings:  3213
Symbols:
+ -[PHAWallpaperSuggestionRefreshSession _removeIfNeededFeaturedContent:forceImmediate:withCompletion:]
+ -[PHAWallpaperSuggestionRefreshSession refreshPosterDescriptorsWithProgressReporter:forceImmediate:completion:]
+ -[PHAWallpaperSuggestionRefreshSession reloadWallpaperSuggestionsForUUIDs:forceImmediate:progress:error:]
+ GCC_except_table1257
+ GCC_except_table1264
+ GCC_except_table1276
+ GCC_except_table1282
+ GCC_except_table1324
+ GCC_except_table1553
+ GCC_except_table1681
+ GCC_except_table1695
+ GCC_except_table1877
+ _PLPhotoAnalysisWallpaperReloadForceImmediateKey
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorImNS_9allocatorImEEE20__throw_length_errorB9fqe220106Ev
+ ___101-[PHAWallpaperSuggestionRefreshSession _removeIfNeededFeaturedContent:forceImmediate:withCompletion:]_block_invoke
+ ___105-[PHAWallpaperSuggestionRefreshSession reloadWallpaperSuggestionsForUUIDs:forceImmediate:progress:error:]_block_invoke
+ ___105-[PHAWallpaperSuggestionRefreshSession reloadWallpaperSuggestionsForUUIDs:forceImmediate:progress:error:]_block_invoke_2
+ ___111-[PHAWallpaperSuggestionRefreshSession refreshPosterDescriptorsWithProgressReporter:forceImmediate:completion:]_block_invoke
+ ___111-[PHAWallpaperSuggestionRefreshSession refreshPosterDescriptorsWithProgressReporter:forceImmediate:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_73_e8_32s40s48s56bs64r_e29_v24?0"NSArray"8"NSError"16ls32l8s56l8r64l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72r_e20_v20?0B8"NSError"12lr72l8s32l8s40l8s64l8s48l8s56l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72r_e5_v8?0ls32l8s64l8s40l8r72l8s48l8s56l8
- -[PHAWallpaperSuggestionRefreshSession _removeIfNeededFeaturedContent:withCompletion:]
- GCC_except_table1255
- GCC_except_table1262
- GCC_except_table1274
- GCC_except_table1280
- GCC_except_table1319
- GCC_except_table1548
- GCC_except_table1676
- GCC_except_table1690
- GCC_except_table1872
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorImNS_9allocatorImEEE20__throw_length_errorB9fqe220100Ev
- ___86-[PHAWallpaperSuggestionRefreshSession _removeIfNeededFeaturedContent:withCompletion:]_block_invoke
- ___90-[PHAWallpaperSuggestionRefreshSession reloadWallpaperSuggestionsForUUIDs:progress:error:]_block_invoke
- ___90-[PHAWallpaperSuggestionRefreshSession reloadWallpaperSuggestionsForUUIDs:progress:error:]_block_invoke_2
- ___96-[PHAWallpaperSuggestionRefreshSession refreshPosterDescriptorsWithProgressReporter:completion:]_block_invoke
- ___block_descriptor_72_e8_32s40s48s56bs64r_e29_v24?0"NSArray"8"NSError"16ls32l8s56l8r64l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56s64bs72r_e20_v20?0B8"NSError"12lr72l8s32l8s40l8s64l8s48l8s56l8
- ___block_descriptor_80_e8_32s40s48s56s64bs72r_e5_v8?0ls32l8s64l8s40l8r72l8s48l8s56l8
CStrings:
+ "FeaturedContentAllowedToggled"
+ "[PHAStorytellingClientRequestHandler] reloadWallpaperSuggestions: forceImmediate=YES (user-initiated)"
+ "[PHAWallpaperSuggestionRefreshSession] Failed to %s poster descriptor update: %@"
+ "[PHAWallpaperSuggestionRefreshSession] Failed to request immediate removal of existing poster descriptors: %@"
+ "[PHAWallpaperSuggestionRefreshSession] Featured content is not allowed and there are existing poster descriptors, attempting to remove them (forceImmediate=%{BOOL}d)"
+ "[PHAWallpaperSuggestionRefreshSession] Successfully %s poster descriptor update"
+ "[PHAWallpaperSuggestionRefreshSession] Successfully requested immediate removal of existing poster descriptors (now %d)"
+ "queue"
+ "queued"
+ "request immediate"
+ "requested immediate"
- "[PHAWallpaperSuggestionRefreshSession] Failed to queue poster descriptor update: %@"
- "[PHAWallpaperSuggestionRefreshSession] Featured content is not allowed and there are existing poster descriptors, attempting to remove them"
- "[PHAWallpaperSuggestionRefreshSession] Successfully queued poster descriptor update"
```
