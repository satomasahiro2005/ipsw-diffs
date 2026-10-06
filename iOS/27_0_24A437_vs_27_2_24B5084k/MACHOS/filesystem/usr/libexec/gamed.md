## gamed

> `/usr/libexec/gamed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a5628` | `0x2a630c` | **`+0xce4`** |
| `__TEXT.__unwind_info` | `0x9588` | `0x9190` | **`-0x3f8`** |
| `__TEXT.__objc_methname` | `0x23c57` | `0x23dd7` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x145d8` | `0x14708` | **`+0x130`** |
| `__TEXT.__cstring` | `0x196f1` | `0x19801` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0x1bbc0` | `0x1bcc0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x19239` | `0x19319` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0xe28c` | `0xe2ec` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xc7a0` | `0xc7e8` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x8288` | `0x82c8` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x30d0` | `0x30e4` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x1b50` | `0x1b64` | **`+0x14`** |
| `__DATA.__bss` | `0x51d8` | `0x51e8` | **`+0x10`** |
| `__DATA.__objc_const` | `0x20ff0` | `0x21000` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4ac0` | `0x4ad0` | **`+0x10`** |
| `__TEXT.__const` | `0x13580` | `0x13590` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2578` | `0x2580` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x22c0` | `0x22c8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x568` | `0x570` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x690` | `0x694` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-821.0.25.0.0
+821.1.8.0.0

-  Functions: 12494
-  Symbols:   2579
-  CStrings:  10607
+  Functions: 12527
+  Symbols:   2581
+  CStrings:  10621
Symbols:
+ _$s12GameServices16DataRefreshScopeO7missingyA2CmFWC
+ _$s16GameServicesCore0aB12DataProviderC14syncAllPendingyyYaF
+ _$s16GameServicesCore0aB12DataProviderC14syncAllPendingyyYaFTu
+ _$s16GameServicesCore0aB7SupportP11sendRequest4data7headers2to10Foundation4DataVAE_Sd8cacheTTLtAJ_SDyS2SGSStYaKFTq
- _$s12GameServices16DataRefreshScopeO3allyA2CmFWC
- _$s16GameServicesCore0aB7SupportP11sendRequest4data7headers2to10Foundation4DataVAJ_SDyS2SGSStYaKFTq
CStrings:
+ "-[GKGameServicePrivate loadGamesPlayedSummariesForPlayerID:limit:withinSecs:handler:]_block_invoke"
+ "-[GamesPlayedSummaryList(GKQuery) gkCoversRequestWithinSecs:]"
+ "-[GamesPlayedSummaryList(GKQuery) gkHasServeableCache]"
+ "A games played summaries refresh is already in flight for : %@"
+ "Games played summaries cache does not satisfy request (withinSecs: %@); cached withinSecs: %@, fetchedAt: %@. Going to server for : %@"
+ "Returning expired games played descriptors for %@ and refreshing in the background"
+ "beginBackgroundGamesPlayedSummariesRefreshForPlayerID:"
+ "com.apple.gamed.GKGameService.gamesPlayedSummaries.refresh"
+ "endBackgroundGamesPlayedSummariesRefreshForPlayerID:"
+ "gamesPlayedSummariesRefreshQueue"
+ "gkCoversRequestWithinSecs:"
+ "gkHasServeableCache"
+ "loadGamesPlayedSummariesForPlayerID:limit:withinSecs:handler:"
+ "networkManagerIgnoreCache is set. Going to server for : %@"
+ "refreshGamesPlayedSummariesInBackgroundForPlayerID:limit:withinSecs:"
+ "syncAllPendingWithCompletionHandler:"
- "Encountered a fetch error while trying to lookup a game list: %@"
- "Going to server for games played descriptors for : %@"
```
