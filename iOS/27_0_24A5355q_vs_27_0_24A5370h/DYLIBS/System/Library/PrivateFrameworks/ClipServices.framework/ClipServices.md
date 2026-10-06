## ClipServices

> `/System/Library/PrivateFrameworks/ClipServices.framework/ClipServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38368` | `0x382a0` | **`-0xc8`** |
| `__TEXT.__unwind_info` | `0x10b8` | `0x10c0` | **`+0x8`** |

### Other Changes

```text
Functions:
~ -[CPSWebClipStore _enumerateAndMapClipsWithBlock:] : 820 -> 816
~ -[CPSClipCleanupManager dealloc] : 524 -> 516
~ ___61-[CPSClipCleanupManager removeClipsByUser:completionHandler:]_block_invoke : 628 -> 624
~ ___71-[CPSClipCleanupManager removeFailedClipInstallsWithCompletionHandler:]_block_invoke : 732 -> 728
~ ___71-[CPSClipCleanupManager removeFailedClipInstallsWithCompletionHandler:]_block_invoke.16 : 744 -> 736
~ ___83-[CPSClipCleanupManager uninstallClipsWithParentAppInstalledWithCompletionHandler:]_block_invoke : 904 -> 896
~ ___84-[CPSClipCleanupManager _didReceiveApplicationChangedNotification:operationHandler:]_block_invoke : 256 -> 252
~ ___66-[CPSClipCleanupManager _didReceiveMCSettingsChangedNotification:]_block_invoke : 1100 -> 1096
~ ___55-[CPSClipCleanupManager assertionTargetProcessDidExit:]_block_invoke : 536 -> 532
~ ___65-[CPSClipCleanupManager _applicationsDidChange:operationHandler:]_block_invoke_2 : 256 -> 252
~ -[CPSClipCleanupManager _shouldDeleteClipWithRecord:parentRecord:] : 408 -> 404
~ -[CPSClipCleanupManager _handleNewInstalledAppWithBundleID:] : 1544 -> 1524
~ -[CPSClipCleanupManager _transferTCCPermissionsFromClipWithBundleID:toParentAppWithBundleID:] : 556 -> 552
~ -[NSString(ClipServicesExtras) cps_sha256String] : 164 -> 172
~ -[CPSSessionManager _handleMemoryPressure:] : 360 -> 356
~ ___54-[CPSSessionManager handleManagedConfigurationChanged]_block_invoke : 360 -> 356
~ ___36-[CPSSessionManager _localeChanged:]_block_invoke : 360 -> 356
~ -[CPSWebClipStore _redirectPoweredByWebClipsWithApplicationBundleIdentifier:toParentApplicationBundleIdentifier:errors:] : 448 -> 444
~ -[CPSWebClipStore _removeWebClipsWithApplicationBundleIdentifier:errors:] : 456 -> 452
~ ___84-[CPSWebClipStore removeWebClipsWithApplicationBundleIdentifiers:completionHandler:]_block_invoke : 464 -> 460
~ ___83-[CPSWebClipStore updateWebClipTitle:forAppClipBundleIdentifier:completionHandler:]_block_invoke : 404 -> 400
~ -[CPSWebClipStore _createOrUpdateExistingWebClipWithClipMetadata:createdNewWebClip:error:] : 844 -> 840
~ -[CPSWebClipStore _webClipsBackedbyAppClipIdentifier:] : 360 -> 356
~ ___63-[CPSWebClipStore purgeDuplicateWebClipsWithCompletionHandler:]_block_invoke : 520 -> 516
~ ___63-[CPSWebClipStore purgeDuplicateWebClipsWithCompletionHandler:]_block_invoke_2 : 504 -> 500
~ ___73-[CPSWebClipStore removePoweredByWebClipsLastActivatedBefore:completion:]_block_invoke : 808 -> 804
~ -[CPSValidationResult availabilities] : 372 -> 368
~ -[CPSSession _didDetermineAvailability:] : 344 -> 340
~ -[CPSSession _notifyObserversOfMetadataFetchResultUpdates:] : 424 -> 416
~ -[CPSSession _didFetchBusinessIconWithURL:] : 276 -> 272
~ ___43-[CPSSession didCompleteTestSessionAtTime:]_block_invoke : 264 -> 260
~ ___90-[CPSSession _retrieveImageWithURL:didFetchImage:fileURL:fetchCompletion:proxyCompletion:]_block_invoke : 348 -> 344
~ ___58-[CPSSession installationControllerDidInstallPlaceholder:]_block_invoke : 404 -> 400
~ ___55-[CPSSession installationController:didUpdateProgress:]_block_invoke : 292 -> 288
~ ___56-[CPSSession installationController:didFinishWithError:]_block_invoke : 368 -> 364
~ +[CPSUtilities _associatedDomainIsApprovedForURL:applicationIdentifier:serviceType:] : 484 -> 480
~ -[CPSImageStore _purgeOldFilesInDirectory:timeToLive:] : 656 -> 652
~ -[CPSClipMetadata _thinnedSizeWithVariantsInfo:productVariants:productVersion:] : 956 -> 948
~ ___79-[CPSClipMetadata _thinnedSizeWithVariantsInfo:productVariants:productVersion:]_block_invoke : 400 -> 396
~ -[CPSClipMetadata hasValidAssociatedDomainsToLaunchAppClip] : 640 -> 636
~ -[CPSPromise _flushCompletionBlocks] : 292 -> 288
~ +[CPSDeveloperOverride loadAllOverridesIfNeeded] : 372 -> 368
~ +[CPSDeveloperOverride overrideForURL:] : 392 -> 388
~ +[CPSDeveloperOverride persistAllOverrides] : 348 -> 344
```
