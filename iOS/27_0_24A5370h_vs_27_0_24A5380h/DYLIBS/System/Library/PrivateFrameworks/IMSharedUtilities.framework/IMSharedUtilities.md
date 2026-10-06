## IMSharedUtilities

> `/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35d71c` | `0x3598f4` | **`-0x3e28`** |
| `__TEXT.__oslogstring` | `0x1e586` | `0x1e196` | **`-0x3f0`** |
| `__AUTH_CONST.__objc_const` | `0x26bc0` | `0x26f88` | **`+0x3c8`** |
| `__DATA_DIRTY.__bss` | `0xca8` | `0xf70` | **`+0x2c8`** |
| `__DATA.__bss` | `0x38870` | `0x38620` | **`-0x250`** |
| `__DATA_DIRTY.__objc_data` | `0x1310` | `0x1518` | **`+0x208`** |
| `__AUTH.__objc_data` | `0x8388` | `0x81d0` | **`-0x1b8`** |
| `__DATA_DIRTY.__data` | `0xd18` | `0xec8` | **`+0x1b0`** |
| `__TEXT.__objc_methlist` | `0x18c60` | `0x18df8` | **`+0x198`** |
| `__AUTH_CONST.__cfstring` | `0x23860` | `0x239e0` | **`+0x180`** |
| `__TEXT.__constg_swiftt` | `0x6698` | `0x67bc` | **`+0x124`** |
| `__TEXT.__cstring` | `0x27423` | `0x27543` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x752c` | `0x763c` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0xe86c` | `0xe78c` | **`-0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0xcfb0` | `0xd070` | **`+0xc0`** |
| `__TEXT.__const` | `0x1f210` | `0x1f2c0` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x17560` | `0x175f0` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x7cdc` | `0x7d68` | **`+0x8c`** |
| `__DATA.__data` | `0xa7d8` | `0xa788` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xf4d0` | `0xf518` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x518` | `0x4e4` | **`-0x34`** |
| `__TEXT.__swift5_reflstr` | `0x6963` | `0x6993` | **`+0x30`** |
| `__AUTH.__data` | `0x6520` | `0x6548` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2bc8` | `0x2bb0` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xdb8` | `0xdd0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1054` | `0x1068` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x310` | `0x2fc` | **`-0x14`** |
| `__DATA_CONST.__const` | `0x6bc8` | `0x6bd8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x9d44` | `0x9d50` | **`+0xc`** |
| `__TEXT.__swift5_capture` | `0x14e0` | `0x14d4` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0x800` | `0x80c` | **`+0xc`** |
| `__DATA.__common` | `0x158` | `0x150` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x648` | `0x650` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1d28` | `0x1d30` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xac` | `0xb4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x36c` | `0x370` | **`+0x4`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 20780
-  Symbols:   4157
-  CStrings:  7960
+  Functions: 20803
+  Symbols:   4164
+  CStrings:  7958
Symbols:
+ _IMCloudKitAttachmentDownloadHistoryFinished
+ _IMContactUtilitiesDisplayNameKey
+ _IMContactUtilitiesShortNameKey
+ _IMMetricsCollectorEventCKVEndpointFailure
+ _IMSharedBalloonPreviewSummaryForCustomAcknowledgementMessageWithSenderMap
+ _IMSharedBalloonPreviewSummaryForPollAddChoiceMessageWithSenderMap
+ _OBJC_CLASS_$_IMPersistentTaskContentDateDescriptor
+ _OBJC_METACLASS_$_IMPersistentTaskContentDateDescriptor
+ _swift_retain_x10
- _swift_release_x10
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "<IMPersistentTaskContentDateDescriptor Phase=%ld ContentStart=%@ ContentEnd=%@ IncludesUndated=%@>"
+ "<IMPersistentTaskReport Group=%@ Flag=%@ Lane=%@ Reason=%@ Count=%lu Window=%@>"
+ "<nil> (due to nil operationStatus)"
+ "A"
+ "AttachmentDownloadHistoryFinished"
+ "DAS"
+ "Failed to flush manifest before UV close. Error: %@"
+ "IMCSPhaseOneMonths"
+ "IMCSPhaseZeroMonths"
+ "PhasedSpotlightIndexing"
+ "PhasedSpotlightIndexingEnabled"
+ "Reporting spam not supported for RCS registration state %s"
+ "Reporting spam requires configuration, but there is no configuration for subscription %@"
+ "_isPhasedSpotlightIndexingEnabled"
+ "ckv_underlying_error_code"
+ "ckv_underlying_error_domain"
+ "com.apple.Messages.IMMetricsCollectorEventCKVEndpointFailure"
+ "contentDateDescriptor"
+ "now"
+ "shortName"
+ "support_phased_processing"
+ "unbounded"
+ "underlyingErrorCode"
+ "underlyingErrorDomain"
- "%s Could not construct a preview URL for guid: %s."
- "%s Did not find a preview extension to use when looking for media object previews to delete."
- "%s Did not find an original file transfer URL for guid: %s. Skipping search for previews."
- "%s Error attempting to remove file: %s. Error: %@"
- "%s url was in progress when manifest evicted it, we will not delete it: %s"
- "/Intents/RemoteIntentFileManifest.db"
- "<IMPersistentTaskReport Group=%@ Flag=%@ Lane=%@ Reason=%@ Count=%lu>"
- "Attempted to evict oldest file, but no file was evicted. The cache count may be incorrect."
- "Calistoga"
- "CalistogaEnabled"
- "Current cache count: %ld. Updated most recent file transfer for guid: %s, new file paths: %s. All known paths for this guid: %s"
- "Deleting an additional preview url found during eviction for %s: %s"
- "Deleting evicted file paths for guid: %s, files: %s"
- "Failed to initialize shared RemoteIntentFileManifest. The file cache may be in an inconsistent state."
- "Failed to return a common path for %s because the base user vault directory was not found."
- "IconServices"
- "RemoteIntentUserVault"
- "SwiftUI"
- "_isIconServicesCalistogaIconsEnabled"
- "_isSwiftUICalistogaIconsEnabled"
- "delete(evictedFiles:for:)"
- "deleteMediaObjectPreviews(for:)"
- "init with delegate: %s, cacheLimit: %ld, current count: %ld. Pruning to limit if necessary."
- "manifestDidEvictGUID: %s with files: %s"
- "pruneToLimit evicted %ld files. Current count: %ld"
- "pruneToLimit: %ld, current count: %ld"
```
