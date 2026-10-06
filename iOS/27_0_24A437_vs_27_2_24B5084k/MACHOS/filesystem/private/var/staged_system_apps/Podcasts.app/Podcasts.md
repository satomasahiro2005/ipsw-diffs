## Podcasts

> `/private/var/staged_system_apps/Podcasts.app/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eb120` | `0x3ecb30` | **`+0x1a10`** |
| `__TEXT.__oslogstring` | `0x19125` | `0x19425` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x1c850` | `0x1c6a0` | **`-0x1b0`** |
| `__TEXT.__eh_frame` | `0xb8f8` | `0xba78` | **`+0x180`** |
| `__DATA.__data` | `0x144a8` | `0x14338` | **`-0x170`** |
| `__TEXT.__auth_stubs` | `0xcaa0` | `0xcbe0` | **`+0x140`** |
| `__DATA.__objc_const` | `0x26198` | `0x26070` | **`-0x128`** |
| `__TEXT.__swift5_capture` | `0x694c` | `0x688c` | **`-0xc0`** |
| `__DATA_CONST.__auth_got` | `0x6560` | `0x6600` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x3ae25` | `0x3aec5` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x9140` | `0x90b4` | **`-0x8c`** |
| `__TEXT.__objc_stubs` | `0x2b260` | `0x2b2e0` | **`+0x80`** |
| `__TEXT.__const` | `0x15e34` | `0x15dd4` | **`-0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x2fd8` | `0x2fa0` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x1176c` | `0x11736` | **`-0x36`** |
| `__TEXT.__swift5_fieldmd` | `0x63f4` | `0x63c0` | **`-0x34`** |
| `__TEXT.__cstring` | `0x1128a` | `0x112ba` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x5067` | `0x5037` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0xd0c0` | `0xd0e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x13b08` | `0x13b28` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x40d0` | `0x40e0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x6b55` | `0x6b45` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x900` | `0x910` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x3e0` | `0x3ec` | **`+0xc`** |
| `__DATA.__objc_data` | `0xb790` | `0xb788` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd98` | `0xd90` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4060` | `0x4068` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xe54` | `0xe50` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x68c` | `0x688` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x334` | `0x338` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4027.110.2.0.0
+4027.210.23.1.0

+  - @rpath/JetIncubation.framework/JetIncubation

+  - @rpath/PodcastsInsights.framework/PodcastsInsights
+  - @rpath/PodcastsLogging.framework/PodcastsLogging

-  Functions: 18122
-  Symbols:   6131
-  CStrings:  14235
+  Functions: 18106
+  Symbols:   6148
+  CStrings:  14242
Symbols:
+ _$s10PodcastsUI11AssetCachesV14carPlayArtwork0A10Foundation11CacheDomainVyAA08PreparedG7RequestVSo7UIImageCAE15InMemorySizableAAyHCg1_Gvg
+ _$s15PodcastsActions34OpenTapToRadarActionImplementationV9JetEngine0gH0AAMc
+ _$s15PodcastsActions34OpenTapToRadarActionImplementationVACycfC
+ _$s15PodcastsActions34OpenTapToRadarActionImplementationVMa
+ _$s16PodcastsInsights02isB7EnabledSbyF
+ _$s16PodcastsInsights07DismissB26BannerActionImplementationV9JetEngine0eF0AAMc
+ _$s16PodcastsInsights07DismissB26BannerActionImplementationVACycfC
+ _$s16PodcastsInsights07DismissB26BannerActionImplementationVMa
+ _$s18PodcastsFoundation14ArtworkRequestV12displayScale12CoreGraphics7CGFloatVvg
+ _$s18PodcastsFoundation18InMemoryAssetCacheC5store5asset2atyq__xtF
+ _$s18PodcastsFoundation18MetricsAppExitTypeV10taskSwitchACvgZ
+ _$s18PodcastsFoundation18MetricsAppExitTypeV4quitACvgZ
+ _$s18PodcastsFoundation19EpisodeListSettingsV8ShelfKitE11newEpisodesyACSayAD0C0CGFZ
+ _$s18PodcastsFoundation19MetricsAppEnterTypeV10taskSwitchACvgZ
+ _$s18PodcastsFoundation19MetricsAppEnterTypeV4linkACvgZ
+ _$s18PodcastsFoundation19MetricsAppEnterTypeV6launchACvgZ
+ _$s18PodcastsFoundation24ExplicitContentPresenterC6symbolSSvg
+ _$s18PodcastsFoundation24ExplicitContentPresenterCMa
+ _$s23ShelfKitCollectionViews25InsightsHostingControllerCMa
+ _$s8ShelfKit17MarkEpisodesScopeO03allD0yA2CmFWC
+ _$s8ShelfKit17MarkEpisodesScopeO8filteredyA2CmFWC
+ _$s8ShelfKit17MarkEpisodesScopeOMa
+ _$s8ShelfKit17MarkEpisodesScopeOMn
+ _$s8ShelfKit17StorePageProviderC8asPartOf7pageURL0I09isCarPlayAC9JetEngine15BaseObjectGraphC_10Foundation0J0VSgAA0D0CSgSbtcfc
+ _$s8ShelfKit21ShowMetadataFormatterV15carPlaySubtitle4fromSSSayAA11HeaderModelO0D9ComponentOG_tFZ
+ _$s8ShelfKit31LibraryActionControllerProtocolP017markEpisodesSheetD02as17episodesPredicate5scopeAA0iD0CSo18MTEpisodePlayStateV_So11NSPredicateCAA04MarkH5ScopeOtFTq
+ _$s8ShelfKit31LibraryActionControllerProtocolP21handleMarkingEpisodes2as6source04baseI9Predicate5scopeySo18MTEpisodePlayStateV_10PodcastsUI18PresentationSourceVSo11NSPredicateCAA04MarkI5ScopeOtFTj
+ _$s8ShelfKit31LibraryActionControllerProtocolP21handleMarkingEpisodes2as6source04baseI9Predicate5scopeySo18MTEpisodePlayStateV_10PodcastsUI18PresentationSourceVSo11NSPredicateCAA04MarkI5ScopeOtFTq
+ _$s8ShelfKit7EpisodeC18firstAvailableDate10Foundation0F0VSgvg
+ _$s9JetEngine19AppMetricsPresenterC8ShelfKitE7didExit8withType5usingy18PodcastsFoundation0dciK0V_AA0D13FieldsContextVtF
+ _$s9JetEngine19AppMetricsPresenterC8ShelfKitE8didEnter8withType5usingy18PodcastsFoundation0dciK0V_AA0D13FieldsContextVtF
+ _$s9JetEngine19AppMetricsPresenterCMa
+ _$sSo12CGContextRefa12CoreGraphicsE4draw_2in8byTilingySo07CGImageB0a_So6CGRectVSbtF
+ _CGBitmapContextCreate
+ _CGBitmapContextCreateImage
+ _CGColorSpaceCreateWithName
+ _CGColorSpaceGetModel
+ _CGContextSetInterpolationQuality
+ _CGImageGetColorSpace
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _kCGColorSpaceSRGB
- _$s10PodcastsUI11AssetCachesV15preparedArtwork0A10Foundation11CacheDomainVyAA08PreparedF7RequestVSo7UIImageCAE15InMemorySizableAAyHCg1_Gvg
- _$s10PodcastsUI24ExplicitContentPresenterC6symbolSSvg
- _$s10PodcastsUI24ExplicitContentPresenterCMa
- _$s8ShelfKit17StorePageProviderC8asPartOf7pageURL0I0AC9JetEngine15BaseObjectGraphC_10Foundation0J0VSgAA0D0CSgtcfc
- _$s8ShelfKit19AppExitMetricsEventO0D4KindO10taskSwitchyA2EmFWC
- _$s8ShelfKit19AppExitMetricsEventO0D4KindO4quityA2EmFWC
- _$s8ShelfKit19AppExitMetricsEventO0D4KindOMa
- _$s8ShelfKit19AppExitMetricsEventO8makeData8exitKind9JetEngine0eH0VAC0dJ0O_tFZ
- _$s8ShelfKit20AppEnterMetricsEventO0D4KindO10taskSwitchyA2EmFWC
- _$s8ShelfKit20AppEnterMetricsEventO0D4KindO4linkyA2EmFWC
- _$s8ShelfKit20AppEnterMetricsEventO0D4KindO6launchyA2EmFWC
- _$s8ShelfKit20AppEnterMetricsEventO0D4KindOMa
- _$s8ShelfKit20AppEnterMetricsEventO0D4KindOMn
- _$s8ShelfKit20AppEnterMetricsEventO8makeData9enterKind9JetEngine0eH0VAC0dJ0O_tFZ
- _$s8ShelfKit21ShowMetadataFormatterV15carPlaySubtitle4from14explicitSymbolSSSayAA11HeaderModelO0D9ComponentOG_SSSgtFZ
- _$s8ShelfKit31LibraryActionControllerProtocolP020markAllAsPlayedSheetD017episodesPredicateAA0kD0CSo11NSPredicateC_tFTq
- _$s8ShelfKit31LibraryActionControllerProtocolP022markAllAsUnplayedSheetD017episodesPredicateAA0kD0CSo11NSPredicateC_tFTq
- _$s8ShelfKit31LibraryActionControllerProtocolP29handleMarkingEpisodesAsPlayed6source04baseI9Predicatey10PodcastsUI18PresentationSourceV_So11NSPredicateCtFTj
- _$s8ShelfKit31LibraryActionControllerProtocolP29handleMarkingEpisodesAsPlayed6source04baseI9Predicatey10PodcastsUI18PresentationSourceV_So11NSPredicateCtFTq
- _$s8ShelfKit31LibraryActionControllerProtocolP31handleMarkingEpisodesAsUnplayed6source04baseI9Predicatey10PodcastsUI18PresentationSourceV_So11NSPredicateCtFTj
- _$s8ShelfKit31LibraryActionControllerProtocolP31handleMarkingEpisodesAsUnplayed6source04baseI9Predicatey10PodcastsUI18PresentationSourceV_So11NSPredicateCtFTq
- _$s9JetEngine15MetricsPipelineVMn
- _$s9JetEngine7PromiseC4join4withACyx_5ValueQyd__tGqd___tAA6FutureRd__lF
- _$s9JetEngine7PromiseCAARlzClEyACyxGSo10AMSPromiseCyxGcfC
- _$sSo17OS_dispatch_queueC18PodcastsFoundationE22metricsProcessingQueueABvgZ
CStrings:
+ "%{public}@ Cannot schedule a playState Get for a restored show without a feedURL."
+ "%{public}@ Feed update for a restored show finished with an error: %@"
+ "CarPlayPrepareBitmap"
+ "MARK_FILTERED_AS_PLAYED_CONFIRMATION"
+ "MARK_FILTERED_AS_UNPLAYED_CONFIRMATION"
+ "MTPlayStateBackfillHasOccurred-183554345"
+ "Restore: feed update finished, scheduling a Get for key `playState:%{private}@`."
+ "Restore: not scheduling a playState Get for %{private}@, its feed update did not complete."
+ "Unable to prepare decoded bitmap for %s (%ldx%ld): failed to create bitmap context."
+ "Unable to prepare decoded bitmap for %s (%ldx%ld): failed to create image from context."
+ "Unable to prepare decoded bitmap for %s: image has no usable CGImage backing."
+ "[Episode Sync] Merged key %{public}@ for show %{public}@: %lu remote entries, %lu local episodes, %lu matched, %lu play dates applied, %lu discarded"
+ "[Episode Sync] No local show for key %{public}@, discarding %lu remote entries"
+ "_beginWatchUpdate"
+ "_endWatchUpdate"
+ "backfillMissingPlayStateIfNeeded"
+ "carPlayArtworkCache"
+ "imageOrientation"
+ "initWithCGImage:scale:orientation:"
+ "playState backfill: %lu of %lu followed shows have never fetched play state. Scheduling a Get for them."
+ "playState backfill: unable to fetch followed shows. %@"
+ "presentSheet(significantChangeVersion:description:in:)"
+ "releaseDate duration "
+ "scheduleMissingPlayStateGetForFeedUrl:feedUpdateSucceeded:"
+ "seasonNumber episodeNumber releaseDate duration "
+ "significantChangeVersion: %s"
+ "startQueue"
+ "updateFeedAndFetchPlayStateForRestoredPodcastUuid:feedUrl:"
- "%@-worker"
- "Metrics Exit Event"
- "Rebuild pending network tasks - RESUMING workQueue: %@."
- "Rebuild pending network tasks - SUSPENDING workQueue: %@."
- "Setting AllPodcastsLastUpdatedDate from update all MAPI call"
- "WELCOME_DESCRIPTION_B"
- "WELCOME_DESCRIPTION_C"
- "_TtC8Podcasts26AppEnterExitEventWatchdoge"
- "clientBundleVersion"
- "episodeNumber releaseDate duration "
- "eventWatchdoge"
- "flushImmediately"
- "hasEverEntered"
- "hasSentExit"
- "lastSignificantChangeVersion: %s, currentVersion: %s"
- "preparedArtworkCache"
- "presentSheet(currentVersion:description:in:)"
- "prettyShortStringWithDuration:"
- "seasonNumber episodeNumber duration "
- "text.page.badge.magnifyingglass"
- "workQueueConcurrent"
```
