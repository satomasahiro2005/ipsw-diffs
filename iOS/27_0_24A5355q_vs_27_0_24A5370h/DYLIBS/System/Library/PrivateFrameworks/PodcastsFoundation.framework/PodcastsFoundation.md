## PodcastsFoundation

> `/System/Library/PrivateFrameworks/PodcastsFoundation.framework/PodcastsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dbab4` | `0x4e0ec0` | **`+0x540c`** |
| `__AUTH_CONST.__const` | `0x2f680` | `0x2fa20` | **`+0x3a0`** |
| `__TEXT.__const` | `0x3bde0` | `0x3c110` | **`+0x330`** |
| `__DATA.__bss` | `0x32018` | `0x32318` | **`+0x300`** |
| `__AUTH_CONST.__objc_const` | `0x1cc58` | `0x1ca70` | **`-0x1e8`** |
| `__TEXT.__swift5_typeref` | `0x18e56` | `0x19036` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x107dd` | `0x1099d` | **`+0x1c0`** |
| `__DATA.__data` | `0x6bc8` | `0x6d38` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0xa400` | `0xa2a0` | **`-0x160`** |
| `__TEXT.__swift5_reflstr` | `0xc59b` | `0xc6db` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x3eb0` | `0x3d88` | **`-0x128`** |
| `__TEXT.__objc_methlist` | `0xbbac` | `0xba8c` | **`-0x120`** |
| `__TEXT.__swift5_fieldmd` | `0xf4e8` | `0xf604` | **`+0x11c`** |
| `__DATA_DIRTY.__objc_data` | `0x5780` | `0x5670` | **`-0x110`** |
| `__TEXT.__constg_swiftt` | `0xfe94` | `0xff70` | **`+0xdc`** |
| `__TEXT.__eh_frame` | `0x148a4` | `0x14980` | **`+0xdc`** |
| `__AUTH.__data` | `0x3028` | `0x30e8` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x12b20` | `0x12a60` | **`-0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6ce8` | `0x6c48` | **`-0xa0`** |
| `__TEXT.__swift5_capture` | `0x6d34` | `0x6dc0` | **`+0x8c`** |
| `__TEXT.__unwind_info` | `0x12440` | `0x124a8` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x3ce8` | `0x3ca0` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0xc04` | `0xbd8` | **`-0x2c`** |
| `__TEXT.__swift5_proto` | `0x2974` | `0x299c` | **`+0x28`** |
| `__TEXT.__ustring` | `0x54` | `0x38` | **`-0x1c`** |
| `__TEXT.__swift_as_entry` | `0x2f0` | `0x308` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x308` | `0x31c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xb08` | `0xaf8` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d0` | `0x1c0` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x1ae78` | `0x1ae68` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x10d10` | `0x10d00` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x112c` | `0x113c` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x6ec` | `0x6f8` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2b38` | `0x2b30` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

-  Functions: 28006
-  Symbols:   12729
-  CStrings:  3783
+  Functions: 28028
+  Symbols:   12704
+  CStrings:  3782
Symbols:
+ +[MTEpisode(NSPredicate) predicateForDownloadedAfterLastPlay]
+ +[MTEpisode(NSPredicate) predicateForSubscriberFilter]
+ __DATA__TtC18PodcastsFoundation20DummyChapterIngester
+ __METACLASS_DATA__TtC18PodcastsFoundation20DummyChapterIngester
+ __OBJC_$_INSTANCE_METHODS_NSManagedObjectContext(MTAdditions|MTChannel|MTEpisode|MTPlaylist|MTPodcast|MTPodcastPlaylistSettings|MTSyncInfo|PodcastsFoundation|PodcastsFoundation1)
+ __PROTOCOLS__TtC18PodcastsFoundation20DummyChapterIngester
+ _associated conformance 18PodcastsFoundation13LibraryEntityO18CategoryCodingKeys33_A205BA2D7D4957E40506C9F222180FD2LLOSHAASQ
+ _associated conformance 18PodcastsFoundation13LibraryEntityO18CategoryCodingKeys33_A205BA2D7D4957E40506C9F222180FD2LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 18PodcastsFoundation13LibraryEntityO18CategoryCodingKeys33_A205BA2D7D4957E40506C9F222180FD2LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 18PodcastsFoundation14PreparingRulesVAA16EpisodeStateRuleAA0F0AaDP_AA0eF0
+ _associated conformance 18PodcastsFoundation19DownloadConsistencyC5IssueO37MissingDownloadedMediaKindsCodingKeys33_0CEBB4924ED5892F4A2435FB5245A6ACLLOSHAASQ
+ _associated conformance 18PodcastsFoundation19DownloadConsistencyC5IssueO37MissingDownloadedMediaKindsCodingKeys33_0CEBB4924ED5892F4A2435FB5245A6ACLLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 18PodcastsFoundation19DownloadConsistencyC5IssueO37MissingDownloadedMediaKindsCodingKeys33_0CEBB4924ED5892F4A2435FB5245A6ACLLOs0J3KeyAAs28CustomDebugStringConvertible
+ _objc_retain_x12
+ _symbolic $s18PodcastsFoundation27OfflineAvailabilityCheckingP
+ _symbolic Say_____11enclosureID______8localURLtG 18PodcastsFoundation9ContentIDO 0B03URLV
+ _symbolic _____ 18PodcastsFoundation13LibraryEntityO18CategoryCodingKeys33_A205BA2D7D4957E40506C9F222180FD2LLO
+ _symbolic _____ 18PodcastsFoundation14PreparingRulesV
+ _symbolic _____ 18PodcastsFoundation17_StubRecordKeeper33_09C954CB175AE13DE0D582A75B94E8D7LLV
+ _symbolic _____ 18PodcastsFoundation19DownloadConsistencyC5IssueO37MissingDownloadedMediaKindsCodingKeys33_0CEBB4924ED5892F4A2435FB5245A6ACLLO
+ _symbolic _____ 18PodcastsFoundation20DummyChapterIngesterC
+ _symbolic _____ 18PodcastsFoundation23ChapterScanningDefaultsO
+ _symbolic _____ 18PodcastsFoundation32MissingMediaKindsIssueIdentifierV
+ _symbolic _____ 18PodcastsFoundation36PopulateMediaKindsResolutionStrategyV
+ _symbolic _____11enclosureID_Shy_____G18resolvedMediaKindst 18PodcastsFoundation9ContentIDO AA24PodcastEpisodeAttributesC9MediaKindO
+ _symbolic _____11enclosureID______8localURLt 18PodcastsFoundation9ContentIDO 0B03URLV
+ _symbolic _____Sg______pSgIeghng_ 18PodcastsFoundation14PlaybackIntentV s5ErrorP
+ _symbolic ___________11enclosureIDShy_____G18resolvedMediaKindst 10Foundation4UUIDV 08PodcastsA09ContentIDO AD24PodcastEpisodeAttributesC9MediaKindO
+ _symbolic ______pSgXw 18PodcastsFoundation27OfflineAvailabilityCheckingP
+ _symbolic _____ySDy_____ypG______pG 7Combine5EmptyV s11AnyHashableV s5ErrorP
+ _symbolic _____ySDyxq_GG 2os21OSAllocatedUnfairLockV
+ _symbolic _____y_____11enclosureID______8localURLtG s23_ContiguousArrayStorageC 18PodcastsFoundation9ContentIDO 0E03URLV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18PodcastsFoundation13LibraryEntityO18CategoryCodingKeys33_A205BA2D7D4957E40506C9F222180FD2LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18PodcastsFoundation19DownloadConsistencyC5IssueO37MissingDownloadedMediaKindsCodingKeys33_0CEBB4924ED5892F4A2435FB5245A6ACLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18PodcastsFoundation13LibraryEntityO18CategoryCodingKeys33_A205BA2D7D4957E40506C9F222180FD2LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18PodcastsFoundation19DownloadConsistencyC5IssueO37MissingDownloadedMediaKindsCodingKeys33_0CEBB4924ED5892F4A2435FB5245A6ACLLO
+ _symbolic _____yxq_GSg 18PodcastsFoundation18InMemoryAssetCacheC
+ _type_layout_string 18PodcastsFoundation32MissingMediaKindsIssueIdentifierV
- +[MTEpisode(NSPredicate) predicateForSubscriberEntitlement]
- +[PFClientUtil supportsStationAppIntents]
- -[IMMetricsAppCloseEvent exitURL]
- -[IMMetricsAppCloseEvent initWithReason:]
- -[IMMetricsAppCloseEvent setExitTypeWithSuspendReason:]
- -[IMMetricsAppCloseEvent setExitURL:]
- -[IMMetricsAppOpenEvent initWithReason:]
- -[IMMetricsAppOpenEvent referringAppName]
- -[IMMetricsAppOpenEvent referringURL]
- -[IMMetricsAppOpenEvent setEnterTypeWithLaunchReason:]
- -[IMMetricsAppOpenEvent setReferringAppName:]
- -[IMMetricsAppOpenEvent setReferringURL:]
- -[MTEpisode(Core) setCleanedTitle:]
- -[NSString(MTAdditions) cleanedTitleStringWithPrefix:]
- -[NSString(MTAdditions) words]
- _IMAMSMetricsEventTypeAppClose
- _IMAMSMetricsEventTypeAppOpen
- _OBJC_CLASS_$_IMMetricsAppCloseEvent
- _OBJC_CLASS_$_IMMetricsAppOpenEvent
- _OBJC_CLASS_$_MTChapter
- _OBJC_METACLASS_$_IMMetricsAppCloseEvent
- _OBJC_METACLASS_$_IMMetricsAppOpenEvent
- _OBJC_METACLASS_$_MTChapter
- __DATA_MTChapter
- __INSTANCE_METHODS_MTChapter
- __METACLASS_DATA_MTChapter
- __OBJC_$_INSTANCE_METHODS_IMMetricsAppCloseEvent
- __OBJC_$_INSTANCE_METHODS_IMMetricsAppOpenEvent
- __OBJC_$_INSTANCE_METHODS_NSManagedObjectContext(MTAdditions|MTChannel|MTEpisode|MTPlaylist|MTPodcast|MTPodcastPlaylistSettings|MTSyncInfo|PodcastsFoundation|PodcastsFoundation1|PodcastsFoundation2)
- __OBJC_$_PROP_LIST_IMMetricsAppCloseEvent
- __OBJC_$_PROP_LIST_IMMetricsAppOpenEvent
- __OBJC_CLASS_RO_$_IMMetricsAppCloseEvent
- __OBJC_CLASS_RO_$_IMMetricsAppOpenEvent
- __OBJC_METACLASS_RO_$_IMMetricsAppCloseEvent
- __OBJC_METACLASS_RO_$_IMMetricsAppOpenEvent
- __PROTOCOL_INSTANCE_METHODS_PFChapterIngester
- __PROTOCOL_METHOD_TYPES_PFChapterIngester
- ___30-[NSString(MTAdditions) words]_block_invoke
- ___36+[PFClientUtil supportsLocalLibrary]_block_invoke
- ___54-[NSString(MTAdditions) cleanedTitleStringWithPrefix:]_block_invoke
- ___block_descriptor_40_e8_32s_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48ls32l8
- ___block_descriptor_72_e8_32s40s48r56r64r_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48ls32l8r48l8r56l8s40l8r64l8
- _associated conformance 18PodcastsFoundation23CoreDataChapterProviderV6ErrorsOSHAASQ
- _associated conformance 18PodcastsFoundation9MTChapterC10FieldNamesOSHAASQ
- _keypath_get_selector_artworkBackgroundColor
- _keypath_get_selector_artworkHeight
- _keypath_get_selector_artworkWidth
- _keypath_get_selector_chapterTypeIntValue
- _keypath_get_selector_id
- _keypath_get_selector_timeframesData
- _keypath_get_selector_title
- _os_feature_enabled_remove_clean_episode_title
- _supportsLocalLibrary.onceToken
- _supportsLocalLibrary.supportsLocalLibrary
- _symbolic SDyxq_G
- _symbolic Say_____GSg______Sg_____SgSdSgt 18PodcastsFoundation7ChapterV AA0C10CollectionV6SourceO AA9PriceTypeO
- _symbolic _____ 18PodcastsFoundation23CoreDataChapterProviderV
- _symbolic _____ 18PodcastsFoundation23CoreDataChapterProviderV6ErrorsO
- _symbolic _____ 18PodcastsFoundation9MTChapterC
- _symbolic _____ 18PodcastsFoundation9MTChapterC10FieldNamesO
- _symbolic _____SgIeghn_ 18PodcastsFoundation14PlaybackIntentV
- _symbolic _____Sg______t 10Foundation3URLV s5Int64V
- _symbolic ypXp
CStrings:
+ " enclosureID resolvedMediaKinds "
+ "%K != nil AND %K > %K"
+ "MaxEndTimeGeneratedLinks"
+ "NewsBriefEntity"
+ "ReachabilityTransformer: Ignoring reachability status since content is available for offline playback."
+ "ReachabilityTransformer: Unhandled error, network is reachable."
+ "Resetting levelType for non top level episodes for show %s - %ld episodes need udpate"
+ "SPT.PPCW01"
+ "SignificantChange"
+ "TVInstrumentation"
+ "[MissingMediaKindsIssueIdentifier] Empty media kinds for %s, skipping"
+ "[MissingMediaKindsIssueIdentifier] Probing %ld enclosures for media kinds"
+ "app.podcasts.PLUS"
+ "app.podcasts.PSUB"
+ "app.podcasts.external"
+ "debugChapterScanningProximityThreshold"
+ "debugChapterScanningSlowdownDuration"
+ "enclosureID resolvedMediaKinds "
+ "missingDownloadedMediaKinds"
+ "offers"
+ "resolvedMediaKinds"
+ "syncKeys.SubscriptionSync.v1.hasEverSyncedSuccessfully"
+ "syncKeys.SubscriptionSync.v3.hasEverSyncedSuccessfully"
- " \n\t,;:：–—-)"
- "MTChapter"
- "PodcastsThinClient"
- "RemoveCleanEpisodeTitle"
- "SnapToChapter"
- "Unable to determine the price type for the episode %{private,mask.hash}s."
- "Unexpected type %{public}s encountered while deleting chapters."
- "Unexpected type %{public}s found in episode's chapters list."
- "[%{private,mask.hash}s] Normalization resulted in missing chapters - raw count %ld, normalized count %ld."
- "[CD/%{private,mask.hash}s] Fetched %ld chapters."
- "[CD/%{private,mask.hash}s] Missing required data:\n  - source: %{private,mask.hash}s\n  - priceType: %{private,mask.hash}s"
- "[CD/%{private,mask.hash}s] No valid chapters found."
- "[CD/%{private,mask.hash}s] Received request."
- "app_close"
- "app_open"
- "backgroundFetch"
- "destinationUrl"
- "launch"
- "quit"
- "refApp"
- "refUrl"
- "syncVersionFlags"
- "taskSwitch"
- "\u200b"
```
