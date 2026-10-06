## SplashBoard

> `/System/Library/PrivateFrameworks/SplashBoard.framework/SplashBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2823c` | `0x28184` | **`-0xb8`** |
| `__TEXT.__gcc_except_tab` | `0xa38` | `0xa34` | **`-0x4`** |

### Other Changes

```diff

-318.100.0.0.0
+320.0.0.0.0
Functions:
~ -[XBApplicationSnapshotManifestImpl _access_snapshotsForGroupIDs:matchingPredicate:] : 528 -> 524
~ -[XBApplicationSnapshotFetchRequest NSSortDescriptors] : 332 -> 328
~ -[XBApplicationSnapshotManifestImpl _access_queue_reapExpiredAndInvalidSnapshots] : 1316 -> 1304
~ -[XBApplicationSnapshotManifestImpl _access_deleteSnapshots:] : 632 -> 628
~ ___99+[XBApplicationSnapshotManifestImpl acquireManifestForContainerIdentity:store:creatingIfNecessary:]_block_invoke : 1212 -> 1208
~ ___61-[XBApplicationSnapshotGroup _validateWithContainerIdentity:]_block_invoke : 420 -> 416
~ -[XBApplicationSnapshotManifestImpl _access_doArchiveWithCompletions:] : 844 -> 840
~ -[XBApplicationCaptureInformation descriptionBuilderWithMultilinePrefix:] : 448 -> 444
~ -[XBApplicationLaunchCompatibilityInfo initWithBundle:] : 2444 -> 2436
~ -[XBDefaultApplicationProvider _allApplicationsFilteredBySystem:bySplashBoard:] : 672 -> 668
~ ___68-[XBApplicationController performPostMigrationLaunchImageGeneration]_block_invoke : 548 -> 544
~ -[XBApplicationController _deleteLegacyCachesSnapshotPathsIfNeeded] : 732 -> 728
~ ___133-[XBApplicationController _captureOrUpdateLaunchImagesForApplications:firstImageIsReady:createCaptureInfo:completionWithCaptureInfo:]_block_invoke : 1688 -> 1684
~ -[XBApplicationController _launchRequestsForApplication:withCompatibilityInfo:] : 724 -> 716
~ ___95-[XBApplicationController _removeLaunchImagesMatchingPredicate:forApplications:forgettingApps:]_block_invoke : 376 -> 372
~ +[XBApplicationSnapshot setSecureCodableCustomExtendedDataClasses:] : 356 -> 352
~ -[XBApplicationSnapshot _manifestQueueDecode_setStore:] : 292 -> 288
~ ___32+[XBVolumeMaintainer configure:]_block_invoke_2 : 1060 -> 1056
~ ___32+[XBVolumeMaintainer configure:]_block_invoke_2.3 : 1008 -> 1004
~ -[XBApplicationSnapshotManifestImpl beginTrackingImageDeletions] : 776 -> 772
~ __fsEventStreamCallback : 840 -> 832
~ ___70-[XBApplicationSnapshotManifestImpl _access_doArchiveWithCompletions:]_block_invoke_2 : 248 -> 244
~ ___79-[XBApplicationSnapshotManifestImpl _access_purgeSnapshotsWithProtectedContent]_block_invoke : 352 -> 348
~ ___76-[XBApplicationSnapshotManifestImpl _access_updateSnapshotsAPFSPurgability:]_block_invoke : 648 -> 644
~ -[XBApplicationSnapshotManifestImpl _access_snapshotsConsideredUnpurgableByAPFS] : 440 -> 436
~ -[XBApplicationSnapshotManifestImpl _access_snapshotsForGroupIDs:] : 376 -> 372
~ -[XBLaunchImageProvider captureLaunchImageForManifest:withCompatibilityInfo:launchRequests:createCaptureInfo:firstImageIsReady:withCompletionHandler:] : 1736 -> 1704
~ -[XBApplicationSnapshotGroup _manifestQueueDecode_setStore:] : 260 -> 256
~ -[XBApplicationSnapshotGroup _validateWithContainerIdentity:] : 1764 -> 1756
~ -[XBApplicationSnapshotGroup _invalidate] : 240 -> 236
~ -[XBApplicationSnapshotGroup encodeWithCoder:] : 376 -> 372
~ ___76-[XBApplicationSnapshotGroup descriptionForStateCaptureWithMultilinePrefix:]_block_invoke : 348 -> 344
~ _XBValidateResource : 1668 -> 1664
```
