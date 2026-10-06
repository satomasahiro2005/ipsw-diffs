## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ee578` | `0x2eedf4` | **`+0x87c`** |
| `__TEXT.__gcc_except_tab` | `0x1f4f4` | `0x1f60c` | **`+0x118`** |
| `__DATA_CONST.__objc_selrefs` | `0x186f0` | `0x187b8` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x98c0` | `0x9938` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0xdd20` | `0xdd80` | **`+0x60`** |
| `__TEXT.__cstring` | `0x10a84` | `0x10ae4` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x24d5c` | `0x24db4` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x88e0` | `0x8930` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xb21f` | `0xb26f` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x4c8` | `0x498` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x2508` | `0x2528` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x33458` | `0x33470` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x37f8` | `0x3810` | **`+0x18`** |
| `__TEXT.__const` | `0x4e50` | `0x4e60` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10298` | `0x102a8` | **`+0x10`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 16270
-  Symbols:   23028
-  CStrings:  3283
+  Functions: 16283
+  Symbols:   23044
+  CStrings:  3286
Symbols:
+ -[Application _scheduleUsageRetentionSettingsSnapshot]
+ -[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]
+ -[BrowserRootViewController isUsingTopCapsule]
+ -[BrowserWindowController _persistLocalTabGroupUUID:forSceneID:]
+ -[BrowserWindowController _persistedLocalTabGroupUUIDForSceneID:]
+ -[BrowserWindowController _removePersistedLocalTabGroupUUIDForSceneID:]
+ -[SearchSuggestionProvider getKeyForQueryString:isCFSearch:]
+ -[SearchSuggestionProvider previousCommittedQuery]
+ -[SearchSuggestionProvider setPreviousCommittedQuery:]
+ -[TabDocument _donateUsageRetentionEventsForExtensionsRunningOnURL:]
+ -[URLCompletionProvider _doUpdateForPrefix:completionQuery:withSearchParameters:]
+ GCC_except_table1014
+ GCC_except_table1021
+ GCC_except_table1326
+ GCC_except_table1330
+ GCC_except_table1332
+ GCC_except_table1335
+ GCC_except_table1338
+ GCC_except_table1346
+ GCC_except_table1353
+ GCC_except_table1361
+ GCC_except_table1363
+ GCC_except_table1436
+ GCC_except_table451
+ GCC_except_table578
+ GCC_except_table588
+ GCC_except_table590
+ GCC_except_table600
+ GCC_except_table622
+ GCC_except_table626
+ GCC_except_table654
+ GCC_except_table662
+ GCC_except_table696
+ GCC_except_table709
+ GCC_except_table808
+ GCC_except_table817
+ GCC_except_table827
+ GCC_except_table830
+ GCC_except_table835
+ GCC_except_table840
+ GCC_except_table850
+ GCC_except_table864
+ GCC_except_table872
+ GCC_except_table886
+ GCC_except_table914
+ GCC_except_table918
+ GCC_except_table923
+ GCC_except_table927
+ GCC_except_table930
+ GCC_except_table945
+ GCC_except_table946
+ GCC_except_table962
+ GCC_except_table965
+ _OBJC_CLASS_$_WBSAppleAccountInformationProvider
+ _OBJC_CLASS_$_WBSSearchSuggestionsCacheKey
+ _OBJC_IVAR_$_CompletionProvider._completionsCache
+ _OBJC_IVAR_$_SearchSuggestionProvider._previousCommittedQuery
+ _WBSPrefixNavigationalIntentThreshold
+ __SFLocalTabGroupUUIDsBySceneIDDefaultsKey
+ ___141-[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]_block_invoke
+ ___141-[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]_block_invoke_2
+ ___141-[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]_block_invoke_3
+ ___54-[Application _scheduleUsageRetentionSettingsSnapshot]_block_invoke
+ ___78-[TabController _updateContextKitSuggestionsForTabGroupWithCompletionHandler:]_block_invoke_4
+ ___block_descriptor_112_ea8_32s40s48s56s64s72s80s88r96w_e17_v16?0"UIImage"8lr88l8w96l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_40_ea8_32bs_e36_v24?0"LPLinkMetadata"8"NSError"16ls32l8
+ ___block_descriptor_56_ea8_32s40bs48r_e5_v8?0lr48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
- -[BrowserRootViewController usesLoweredBar]
- -[URLCompletionProvider _doUpdateForPrefix:filterResultsUsingProfileIdentifier:withSearchParameters:]
- GCC_except_table1027
- GCC_except_table1225
- GCC_except_table1312
- GCC_except_table1317
- GCC_except_table1327
- GCC_except_table1331
- GCC_except_table1334
- GCC_except_table1337
- GCC_except_table1341
- GCC_except_table1347
- GCC_except_table1354
- GCC_except_table1362
- GCC_except_table1435
- GCC_except_table368
- GCC_except_table577
- GCC_except_table583
- GCC_except_table592
- GCC_except_table624
- GCC_except_table634
- GCC_except_table646
- GCC_except_table678
- GCC_except_table690
- GCC_except_table697
- GCC_except_table725
- GCC_except_table741
- GCC_except_table749
- GCC_except_table791
- GCC_except_table798
- GCC_except_table821
- GCC_except_table822
- GCC_except_table871
- GCC_except_table889
- GCC_except_table902
- GCC_except_table921
- GCC_except_table928
- GCC_except_table942
- GCC_except_table958
- GCC_except_table959
- GCC_except_table979
- GCC_except_table984
- _OBJC_CLASS_$_SFExperimentTriggeredFeedback
- _OBJC_IVAR_$_CompletionProvider._completionsByString
- _OBJC_IVAR_$_URLCompletionProvider._bookmarkProvider
- ___45-[StartPageController _resumeBrowsingSection]_block_invoke_10
- ___48-[BrowserController _siriReadThisMenuInvocation]_block_invoke
- ___48-[BrowserController _siriReadThisMenuInvocation]_block_invoke_2
- ___49-[BrowserController _siriReadThisVocalInvocation]_block_invoke
- ___49-[BrowserController _siriReadThisVocalInvocation]_block_invoke_2
- ___75+[TabMenuProvider menuForClusterWithID:title:tabCount:location:dataSource:]_block_invoke_9
- ___block_descriptor_96_ea8_32s40s48s56s64s72s80r88w_e36_v24?0"LPLinkMetadata"8"NSError"16lw88l8r80l8s32l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "Creating new window: uuid = %{public}@, sceneID = %{public}@, reconnected local tab group = %{public}@, retained persisted local tab group = %{public}@"
+ "LastUsageRetentionSettingsSnapshotTime"
+ "Safari requested starting playback because of %{public}@"
+ "Timed out waiting for link metadata; starting playback without a leading image"
+ "app intent based invocation"
+ "menu based invocation"
- "Creating new window: uuid = %{public}@, sceneID = %{public}@"
- "Safari requested starting playback because of app intent based invocation"
- "Safari requested starting playback because of menu based invocation"
```
