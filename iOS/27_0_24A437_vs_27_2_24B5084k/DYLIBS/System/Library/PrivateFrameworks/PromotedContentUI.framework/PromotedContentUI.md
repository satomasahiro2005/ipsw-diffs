## PromotedContentUI

> `/System/Library/PrivateFrameworks/PromotedContentUI.framework/PromotedContentUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1961d4` | `0x1a6950` | **`+0x1077c`** |
| `__TEXT.__const` | `0xe974` | `0xf664` | **`+0xcf0`** |
| `__DATA.__bss` | `0x9a00` | `0xa580` | **`+0xb80`** |
| `__AUTH_CONST.__const` | `0xb358` | `0xbbb0` | **`+0x858`** |
| `__TEXT.__constg_swiftt` | `0x79b8` | `0x80e4` | **`+0x72c`** |
| `__DATA.__data` | `0x2c10` | `0x32f8` | **`+0x6e8`** |
| `__AUTH.__data` | `0x16c8` | `0x1d68` | **`+0x6a0`** |
| `__AUTH_CONST.__objc_const` | `0xac88` | `0xb290` | **`+0x608`** |
| `__TEXT.__swift5_typeref` | `0x6f0e` | `0x74e8` | **`+0x5da`** |
| `__TEXT.__swift5_fieldmd` | `0x5950` | `0x5dc8` | **`+0x478`** |
| `__TEXT.__cstring` | `0x7ab1` | `0x7e51` | **`+0x3a0`** |
| `__TEXT.__swift5_reflstr` | `0x6658` | `0x6968` | **`+0x310`** |
| `__TEXT.__unwind_info` | `0x4bd0` | `0x4e18` | **`+0x248`** |
| `__TEXT.__swift5_capture` | `0x19d8` | `0x1bdc` | **`+0x204`** |
| `__TEXT.__eh_frame` | `0x61d0` | `0x62c8` | **`+0xf8`** |
| `__AUTH_CONST.__auth_got` | `0x35e0` | `0x36c8` | **`+0xe8`** |
| `__TEXT.__swift5_assocty` | `0x9b8` | `0xa68` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x2d38` | `0x2de0` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x5b04` | `0x5a74` | **`-0x90`** |
| `__TEXT.__swift5_proto` | `0x81c` | `0x890` | **`+0x74`** |
| `__TEXT.__swift5_types` | `0x530` | `0x590` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x7390` | `0x73e0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1708` | `0x1750` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x408` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d68` | `0x1da0` | **`+0x38`** |
| `__DATA.__common` | `0x180` | `0x1b0` | **`+0x30`** |
| `__DATA_DIRTY.__objc_data` | `0x43a8` | `0x43d8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x438` | `0x450` | **`+0x18`** |
| `__TEXT.__swift5_protos` | `0x12c` | `0x13c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x20c4` | `0x20cc` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x360` | `0x358` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1cc` | `0x1c4` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x174` | `0x170` | **`-0x4`** |

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Functions: 6543
-  Symbols:   502
-  CStrings:  982
+  Functions: 6771
+  Symbols:   505
+  CStrings:  996
Symbols:
+ _APPerfLogForCategory
+ _AVPlayerItemDidPlayToEndTimeNotification
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_CATransaction
+ _OBJC_CLASS_$_UIHoverGestureRecognizer
+ _UIFontTextStyleBody
+ __os_signpost_emit_with_name_impl
- _NSSelectorFromString
- _UIFontWeightSemibold
- _objc_retainAutorelease
- _swift_deallocBox
CStrings:
+ "%{public}s candidate %ld: product %{public}s ad %{public}s"
+ ", has restricted ad: "
+ "Ads Payload creation - checking for restrictions (fast path via EligibilitySnapshot)"
+ "Capturing App Store age distribution diagnostics for slot %{public}s ads: %{public}s"
+ "Depositing App Store age distribution sample: %s"
+ "Failed to record %{public}s metric: %@"
+ "Incrementality feature is disabled, not reporting slot outcomes"
+ "Judge awarded slot %s no ad: %s"
+ "Judge awarded slot %s to ad %s with %ld price setters"
+ "Judge held back ghost %s for slot %s"
+ "PromotedContentUI.ModalImageAdView"
+ "PromotedContentUI.ModalVideoAdView"
+ "PromotedContentUI/ModalImageAdView.swift"
+ "PromotedContentUI/ModalVideoAdView.swift"
+ "RankableSearchAdData(productId: \""
+ "Sample(effective age: "
+ "SearchOrganicData(productId: \""
+ "Video player did receive AVPlayerItem.didPlayToEndTimeNotification."
+ "Video player did receive UIScene.willDeactivateNotification."
+ "[AdTransparencySheet] Failed to base64 decode transparency payload"
+ "[AdTransparencySheet] Failed to parse ADTransparencyDetails protobuf"
+ "[Error] Interval already ended"
+ "[NewsPrefetchedAdStore] Cache restored from client-prefetched ad data."
+ "[NewsPrefetchedAdStore] Client-prefetched ad data unavailable. Cache restored from daemon-prefetched ad data."
+ "[NewsPrefetchedAdStore] Failed to decode PromotedContent data: %s"
+ "[NewsPrefetchedAdStore] No client-prefetched ad data found."
+ "[NewsPrefetchedAdStore] No daemon-prefetched ad data found."
+ "[NewsPrefetchedAdStore] Unable to restore cache from persisted data. Starting with empty cache."
+ "[SLPFlagCheck] atRequest=%{public}d atRead=%{public}d mismatch=%{public}d"
+ "[SLPFlagCheck] skipped — flagEnabledAtRequest is nil (old cached ad, or the request-time stamp isn't deployed)"
+ "adBadgePlatterBackground"
+ "appleSearchAdsTimeToInit_POISearchHome"
+ "appleSearchAdsTimeToInit_POISearchResults"
+ "appleSearchAdsTimeToPrewarm"
+ "appleSearchAdsTimeToSignedPayload_POISearchHome"
+ "appleSearchAdsTimeToSignedPayload_POISearchResults"
+ "clientPrefetchedNewsAds"
+ "com.apple.ap.appstore.agedistribution"
+ "enableTelemetry=YES"
+ "locationEnabled"
+ "locationEnabled: "
+ "moduleFactoryTimeToMake"
+ "poiAdRankingStrategyTimeToEvaluateIncrementality"
+ "poiAdRankingStrategyTimeToFilterCandidates"
+ "poiAdRankingStrategyTimeToJudgeCandidates"
+ "poiRequestBuilderDeviceInfo"
+ "poiStrategyRegistryBuild"
+ "responseReceived"
- "%{public}s %{public}s candidate %ld: %s"
- "%{public}s %{public}s candidate … %ld more"
- "%{public}s %{public}s candidates: none"
- "%{public}s candidate %ld: %s"
- "%{public}s curating metadata: %s"
- "AVPlayerItemDidPlayToEndTimeNotification"
- "Ads Payload creation - checking for restrictions"
- "Ads Payload signing - Successfully deserialized Full AdRequest:\n%s"
- "Cache restored from persisted PromotedContent data."
- "Cache restored from persisted daemon data."
- "Failed to base64 decode transparency payload"
- "Failed to decode PromotedContent data: %s"
- "Failed to parse ADTransparencyDetails protobuf"
- "Judge awarded slot %s to %s"
- "Judge awarding %s ad %ld: %s"
- "Judge awarding %s ads: none"
- "Judge awarding slots: %s"
- "No persisted ad data found; starting with empty cache."
- "POIAdRankingStrategy - Duplicate organic position set to %s for candidate %s"
- "POIAdRankingStrategy - Evaluating duplicate organic positions for %ld results."
- "POIAdRankingStrategy - FULL CURATED RESULTS (Final Response):\n%s"
- "POIAdRankingStrategy - FULL INPUT RESULTS (Raw Response Candidates):\n%s"
- "POIAdRankingStrategy - FULL RESPONSE METADATA:\n%s"
- "POIAdRankingStrategy - Processing transparency payload."
- "POIAdRankingStrategy - Successfully processed transparency payload."
- "PromotedContentUI.ImageModalAdView"
- "PromotedContentUI.VideoModalAdView"
- "PromotedContentUI/ImageModalAdView.swift"
- "PromotedContentUI/VideoModalAdView.swift"
- "Unable to restore cache from persisted data; starting with empty cache."
- "Video player did receive notification named AVPlayerItemDidPlayToEndTime."
- "[SRP] Incrementality eval took %{public}f s"
- "com.apple.ap.promotedcontentui.videoplayer.audiosession"
- "dictionaryRepresentation"
```
