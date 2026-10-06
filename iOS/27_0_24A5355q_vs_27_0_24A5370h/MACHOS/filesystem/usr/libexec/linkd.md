## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a644c` | `0x1ac550` | **`+0x6104`** |
| `__TEXT.__oslogstring` | `0x519f` | `0x5a8f` | **`+0x8f0`** |
| `__TEXT.__unwind_info` | `0x79d8` | `0x7f90` | **`+0x5b8`** |
| `__TEXT.__eh_frame` | `0x1545c` | `0x159bc` | **`+0x560`** |
| `__DATA_CONST.__const` | `0x107c8` | `0x10b68` | **`+0x3a0`** |
| `__TEXT.__const` | `0x9f30` | `0xa160` | **`+0x230`** |
| `__DATA.__data` | `0x6d30` | `0x6f30` | **`+0x200`** |
| `__TEXT.__constg_swiftt` | `0x3208` | `0x3348` | **`+0x140`** |
| `__TEXT.__cstring` | `0x416f` | `0x42af` | **`+0x140`** |
| `__DATA.__bss` | `0x72f0` | `0x73f0` | **`+0x100`** |
| `__DATA.__objc_const` | `0x3148` | `0x3240` | **`+0xf8`** |
| `__TEXT.__objc_methname` | `0x59dd` | `0x5aad` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x2648` | `0x2710` | **`+0xc8`** |
| `__DATA_CONST.__auth_ptr` | `0x21f0` | `0x2298` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x5098` | `0x5140` | **`+0xa8`** |
| `__TEXT.__swift5_reflstr` | `0x21d1` | `0x2271` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x4a96` | `0x4a14` | **`-0x82`** |
| `__TEXT.__objc_methlist` | `0x161c` | `0x1674` | **`+0x58`** |
| `__DATA.__objc_data` | `0xaa0` | `0xaf0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0xacb` | `0xb1b` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0xb24` | `0xb60` | **`+0x3c`** |
| `__TEXT.__swift_as_entry` | `0xa44` | `0xa78` | **`+0x34`** |
| `__TEXT.__auth_stubs` | `0x3840` | `0x3870` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0xa0c` | `0xa3c` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x180` | `0x1a0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x13d0` | `0x13e8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1c28` | `0x1c40` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x6a0` | `0x688` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x230` | `0x21c` | **`-0x14`** |
| `__DATA_CONST.__got` | `0xeb8` | `0xea8` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x2f8` | `0x304` | **`+0xc`** |
| `__DATA.__common` | `0xf58` | `0xf60` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x588` | `0x58c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-301.0.41.16.106
+301.0.42.7.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 10968
-  Symbols:   1692
-  CStrings:  1758
+  Functions: 11045
+  Symbols:   1696
+  CStrings:  1788
Symbols:
+ _$s15AppIntentsIndex08MetadataC0V011bundlesWithA9ShortcutsSaySSGyKF
+ _$s15AppIntentsIndex08MetadataC0V16siriLanguageCodeSSSgvg
+ _$s27AppIntentsLiveEntitySupport0caD20FeedProtocolInternalMp
+ _$s27AppIntentsLiveEntitySupport0caD20FeedProtocolInternalP6update8removingySo18LNEntityIdentifierC_tYaKFTj
+ _$s27AppIntentsLiveEntitySupport0caD20FeedProtocolInternalP6update8removingySo18LNEntityIdentifierC_tYaKFTjTu
+ _$s27AppIntentsLiveEntitySupport0caD20FeedProtocolInternalP6update9appending25uniquePerBundleIdentifierySo08LNEntityN0C_SbtYaKFTj
+ _$s27AppIntentsLiveEntitySupport0caD20FeedProtocolInternalP6update9appending25uniquePerBundleIdentifierySo08LNEntityN0C_SbtYaKFTjTu
+ _$s27AppIntentsLiveEntitySupport0caD4FeedCMn
+ _$sSo18LNConnectionPolicyC12LinkServicesE7_policy20withBundleIdentifierSo018LNBundleConnectionB0CSS_tFZ
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsCMn
+ _$sSo24LNTranscriptActionSourceV12LinkServicesE11descriptionSSvg
+ _$ss8DurationV7secondsyABSdFZ
+ _LNConnectionRequestTimeout
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
- _$s10AppIntents16EntityIdentifierV04typeD006bundleD008instanceD006stableD0ACSgSS_S3SSgtcfC
- _$s10AppIntents16EntityIdentifierVMa
- _$s10AppIntents16EntityIdentifierVMn
- _$s27AppIntentsLiveEntitySupport0caD12FeedProtocolMp
- _$s27AppIntentsLiveEntitySupport0caD12FeedProtocolP6update8removingy0aB00D10IdentifierV_tYaKFTj
- _$s27AppIntentsLiveEntitySupport0caD12FeedProtocolP6update8removingy0aB00D10IdentifierV_tYaKFTjTu
- _$s27AppIntentsLiveEntitySupport0caD12FeedProtocolP6update9appending25uniquePerBundleIdentifiery0aB00dM0V_SbtYaKFTj
- _$s27AppIntentsLiveEntitySupport0caD12FeedProtocolP6update9appending25uniquePerBundleIdentifiery0aB00dM0V_SbtYaKFTjTu
- _$s27AppIntentsLiveEntitySupport0caD4FeedCAA0cadF8ProtocolAAWP
- _$s27AppIntentsLiveEntitySupport0caD4FeedCMa
- _swift_release_x11
CStrings:
+ "ApplicationService<"
+ "ConstraintValidationService"
+ "ExtensionService"
+ "OS_dispatch_source"
+ "OS_dispatch_source_timer"
+ "Received AppShortcuts skipped, unblocking"
+ "RelevantEntities: Entity missing local identifier for bundle %{public}s"
+ "RelevantEntities: Exception when donating item with identifier %{public}s: for %{public}s error: %@"
+ "RelevantEntities: Exception when removing item with sourceItemIdentifier %{public}s: for %{public}s error: %@"
+ "RelevantEntities: Unable to convert entity(%{public}@) to cascade set item for bundle %{public}s "
+ "RelevantEntities: Unable to deserialize context for %{public}s"
+ "RelevantEntities: Unable to deserialize suggestedEntities for %{public}s"
+ "RelevantEntities: removeAllEntities: finished for %{public}s"
+ "RelevantEntities: removeAllEntities: starting empty full-set donation for %{public}s"
+ "RelevantEntities: removeAllEntitiesForContext: finished for %{public}s, contextHash=%ld — removed=%ld"
+ "RelevantEntities: removeAllEntitiesForContext: found %ld existing suggested item(s) for %{public}s, contextHash=%ld"
+ "RelevantEntities: removeAllEntitiesForContext: received request for %{public}s, contextBytes=%ld"
+ "RelevantEntities: removeEntities: deserialized %ld value(s) and context (hash=%ld) for %{public}s"
+ "RelevantEntities: removeEntities: finished for %{public}s, contextHash=%ld — removed=%ld, skippedNonEntity=%ld, failed=%ld"
+ "RelevantEntities: removeEntities: received request for %{public}s, valuesBytes=%ld, contextBytes=%ld"
+ "RelevantEntities: removeEntitiesAcrossAllContexts: deserialized %ld value(s); resolved %ld source item identifier(s) for %{public}s"
+ "RelevantEntities: removeEntitiesAcrossAllContexts: finished for %{public}s — removed=%ld"
+ "RelevantEntities: removeEntitiesAcrossAllContexts: received request for %{public}s, valuesBytes=%ld"
+ "RelevantEntities: updateEntities(data): deserialized %ld value(s) and context (hash=%ld) for %{public}s"
+ "RelevantEntities: updateEntities(data): received request for %{public}s, valuesBytes=%ld, contextBytes=%ld"
+ "RelevantEntities: updateEntities: finished for %{public}s, contextHash=%ld — addedOrUpdated=%ld, removedStale=%ld, skippedNonEntity=%ld, skippedConversion=%ld, skippedMissingLocalId=%ld, failed=%ld"
+ "RelevantEntities: updateEntities: found %ld existing suggested item(s) for %{public}s, contextHash=%ld"
+ "RelevantEntities: updateEntities: starting incremental donation for %{public}s, contextHash=%ld, incomingValues=%ld"
+ "RelevantEntities: updateSuggestedEntities: deserialized %ld value(s) for %{public}s"
+ "RelevantEntities: updateSuggestedEntities: finished for %{public}s — registered=%ld, skippedNonEntity=%ld, skippedConversion=%ld, skippedMissingLocalId=%ld, failed=%ld"
+ "RelevantEntities: updateSuggestedEntities: starting full-set donation for %{public}s, payload bytes=%ld"
+ "ResetStopwatchIntent"
+ "SuggestedActionsService"
+ "Timed out waiting for the target process to register its listener endpoint with linkd."
+ "Unexpected direct call for app shortcut bundles"
+ "_TtC10LinkDaemon15ProcessRegistry"
+ "appShortcutBundles:"
+ "appShortcutBundlesWithReply:"
+ "appShortcutInterpolationSkipped"
+ "autoShortcutsForBundleIdentifier:localeIdentifier:error:"
+ "awaitListenerEndpoint(forProcessInstanceIdentifier:)"
+ "fetchTimeout"
+ "initWithTypeIdentifier:bundleIdentifier:instanceIdentifier:stableIdentifier:"
+ "startIncrementalSetDonationWithItemType:descriptors:error:"
- "Could not create LSApplicationRecord for %s"
- "Could not create LSLinkBundleRecord from applicationRecord for %s"
- "Entity missing local identifier for bundle %s"
- "Exception when donating item with identifier %s: for %s error: %@"
- "Exception when removing item with sourceItemIdentifier %s: for %s error: %@"
- "Removing suggested entities for %s"
- "StopStopwatchIntent"
- "Unable to convert entity(%@) to cascade set item for bundle %s "
- "Unable to create EntityIdentifier for %s in %s"
- "Unable to deserialize context for %s"
- "Unable to deserialize suggestedEntities for %s"
- "Updating suggested entities for %s"
- "policyWithBundleIdentifier:"
- "startIncrementalSetDonationWithItemType:error:"
```
