## Podcasts

> `/private/var/staged_system_apps/Podcasts.app/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ed86c` | `0x3ea50c` | **`-0x3360`** |
| `__TEXT.__eh_frame` | `0xbb60` | `0xb8f8` | **`-0x268`** |
| `__DATA_CONST.__const` | `0x1c9c8` | `0x1c800` | **`-0x1c8`** |
| `__DATA.__bss` | `0x12b18` | `0x12998` | **`-0x180`** |
| `__TEXT.__const` | `0x15f94` | `0x15e34` | **`-0x160`** |
| `__TEXT.__oslogstring` | `0x18fe5` | `0x19125` | **`+0x140`** |
| `__DATA.__data` | `0x145a8` | `0x144a8` | **`-0x100`** |
| `__TEXT.__unwind_info` | `0xcb00` | `0xca18` | **`-0xe8`** |
| `__TEXT.__cstring` | `0x1109a` | `0x1116a` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x117e4` | `0x11736` | **`-0xae`** |
| `__TEXT.__swift5_reflstr` | `0x6bf5` | `0x6b55` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x3ad95` | `0x3ae25` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x6480` | `0x63f4` | **`-0x8c`** |
| `__DATA_CONST.__cfstring` | `0xaf60` | `0xafc0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x4130` | `0x40d0` | **`-0x60`** |
| `__TEXT.__swift5_capture` | `0x6980` | `0x6924` | **`-0x5c`** |
| `__DATA.__objc_const` | `0x26148` | `0x26198` | **`+0x50`** |
| `__DATA.__objc_data` | `0xb740` | `0xb790` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x917c` | `0x9140` | **`-0x3c`** |
| `__TEXT.__auth_stubs` | `0xcad0` | `0xcaa0` | **`-0x30`** |
| `__TEXT.__swift_as_cont` | `0x928` | `0x900` | **`-0x28`** |
| `__TEXT.__objc_classname` | `0x5047` | `0x5067` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2b240` | `0x2b260` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6578` | `0x6560` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x13af0` | `0x13b08` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x3f4` | `0x3e0` | **`-0x14`** |
| `__TEXT.__gcc_except_tab` | `0x4054` | `0x4060` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0xaf4` | `0xae8` | **`-0xc`** |
| `__DATA.__objc_selrefs` | `0xd0b8` | `0xd0c0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2fe0` | `0x2fd8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd90` | `0xd98` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x694` | `0x68c` | **`-0x8`** |

### Same-size Content Changes

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
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-4027.100.80.0.0
+4027.110.1.0.0

-  Functions: 18165
-  Symbols:   6145
-  CStrings:  14221
+  Functions: 18116
+  Symbols:   6131
+  CStrings:  14232
Symbols:
+ _$s10Foundation3URLV016standardizedFileB0ACvg
+ _$s18PodcastsFoundation16MTMediaEnclosureC20downloadedMediaKindsShyAA24PodcastEpisodeAttributesC0F4KindOGSgvgTj
+ _$s18PodcastsFoundation16MTMediaEnclosureCAA05MediaD8ProtocolAAWP
+ _$s18PodcastsFoundation22EpisodeStateControllerC07refreshD03foryAA0cD10IdentifierO_tFTj
+ _$s18PodcastsFoundation22MediaEnclosureProtocolPAAE9satisfies9mediaKindSbAA24PodcastEpisodeAttributesC0cH0O_tF
+ _$s18PodcastsFoundation25DatabaseMigrationRecorderC11endDataStep_7success12errorMessageyAA0D12RecordHandleCSg_SbSSSgtFZ
+ _$s18PodcastsFoundation25DatabaseMigrationRecorderC13beginDataStep10identifier12batchVersionAA0D12RecordHandleCSgSS_SSSgtFZ
+ _$s18PodcastsFoundation25DatabaseMigrationRecorderCMa
+ _$sSo9MTEpisodeC18PodcastsFoundationE10mediaKindsShyAC24PodcastEpisodeAttributesC9MediaKindOGSgvg
+ _OBJC_CLASS_$_MTDatabaseMigrationRecorder
+ _PFCategoriesInLibraryDidChangeNotification
- _$s15PodcastsActions28RemoveEpisodesDownloadIntentV18episodeIdentifiersACSay0A10Foundation9ContentIDOG_tcfC
- _$s15PodcastsActions28RemoveEpisodesDownloadIntentV9JetEngine0F5ModelAAMc
- _$s15PodcastsActions28RemoveEpisodesDownloadIntentVMa
- _$s18PodcastsFoundation16MTMediaEnclosureC10FieldNamesO16mediaKindsStringyA2EmFWC
- _$s18PodcastsFoundation16MTMediaEnclosureC10FieldNamesO8durationyA2EmFWC
- _$s18PodcastsFoundation16MTMediaEnclosureC10mediaKindsShyAA24PodcastEpisodeAttributesC9MediaKindOGSgvgTj
- _$s18PodcastsFoundation17ArtworkTextColorsV7primary9secondary8tertiary10quaternaryAcA5ColorOSg_A3JtcfC
- _$s18PodcastsFoundation20EpisodeDownloadStateO12downloadableyACSS_tcACmFWC
- _$s18PodcastsFoundation20MTEpisodeDescriptionC10FieldNamesO11hasRichTextyA2EmFWC
- _$s18PodcastsFoundation20MTEpisodeDescriptionC10FieldNamesO4textyA2EmFWC
- _$s18PodcastsFoundation20MTEpisodeDescriptionC10FieldNamesO8rawValueSSvg
- _$s18PodcastsFoundation20MTEpisodeDescriptionC10FieldNamesO9plainTextyA2EmFWC
- _$s18PodcastsFoundation20MTEpisodeDescriptionC10FieldNamesOMa
- _$s18PodcastsFoundation24MediaKindStringConverterO7isVideoySbSSSgFZ
- _$s18PodcastsFoundation5ColorO10descriptorACSS_tKcfC
- _$s7SwiftUI5ImageV_6bundleACSS_So8NSBundleCSgtcfC
- _$sSo9MTEpisodeC18PodcastsFoundationE20downloadedMediaKindsShyAC24PodcastEpisodeAttributesC0E4KindOGSgvg
- _$sSy10FoundationE7compare_7options5range6localeSo18NSComparisonResultVqd___So22NSStringCompareOptionsVSnySS5IndexVGSgAA6LocaleVSgtSyRd__lF
- _kEpisodeDescriptionObject
- _kPodcastArtworkPrimaryColor
- _kPodcastArtworkTemplateURL
- _kPodcastArtworkTextPrimaryColor
- _kPodcastArtworkTextQuaternaryColor
- _kPodcastArtworkTextSecondaryColor
- _kPodcastArtworkTextTertiaryColor
CStrings:
+ "Added %ld downloads, dropped %ld download requests."
+ "Deleting superseded download asset for episode %{public}s"
+ "Episode already downloaded; skipping failure alert for %{public}s."
+ "Existing download already in flight; skipping failure alert for %{public}s."
+ "Failed to delete superseded asset: %{public}s"
+ "Failed to get app icon"
+ "Failed to upgrade to video with error: %s"
+ "MTMigrationHistoryDebugProvider"
+ "MigrationHistory.json"
+ "Presented sheet"
+ "Presenting sheet"
+ "Reset preparing state for episode %{public}s"
+ "Sheet callback: `.success(false)`. Not dismissing."
+ "Sheet callback: `.success(true)`. Dismissing."
+ "Sheet callback: error. %@"
+ "Video upgrade skipped for %{public}s — video already present or unavailable"
+ "[BackfillListenNowEpisode] Backfilling NULL listenNowEpisode -> NO"
+ "[BackfillListenNowEpisode] Updated %ld episodes"
+ "[Playlist Update] (%{public}@ - '%@') refreshed show '%@' -> %lu episode(s) (saved)"
+ "[Playlist Update] Regenerated station (%{public}@ - '%@'): %lu show(s) refreshed, %lu episode(s) total"
+ "[Playlist Update] Regenerating station (%{public}@ - '%@') across %lu show(s)"
+ "com.apple.podcasts.db.backfillListenNowEpisode-v27A2"
+ "coreDataMigrationFailed"
+ "isApprovalRequired: %{bool}d"
+ "libraryDataMigrationIncomplete"
+ "recordLibraryRebuildWithReason:oldLibraryVersion:newLibraryVersion:oldCoreDataVersion:newCoreDataVersion:coreDataMigrationCompleted:"
- "%K != NULL AND (%K > 0 OR %K < 0)"
- "%K == 0 AND %K.%K == 0"
- "Added %d downloads."
- "Approval flow failed: %@"
- "Approval is empty. Require an approval."
- "Reset preparing state to downloadable for episode %{public}s"
- "Validator comparing versions. approved: %s, latest: %s, isRequired: %{bool}d"
- "Video upgrade: removing completed audio download for episode %{public}s"
- "[FixRSSArtworkToken] Context unavailable"
- "[FixRSSArtworkToken] Fixing %ld episodes"
- "[FixRSSArtworkToken] Migration complete"
- "[FixRSSArtworkToken] Music library is unavailable"
- "[FixRSSArtworkToken] No RSS episodes with broken tokens found"
- "addArtwork(_:to:)"
- "com.apple.podcasts.artwork.sideloaded-artwork-token"
```
