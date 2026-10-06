## SpaceAttribution

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/SpaceAttribution`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13864` | `0x1380c` | **`-0x58`** |

### Other Changes

```diff

-488.0.0.0.0
+490.0.0.0.0
Functions:
~ +[SASupport getFSPurgeableDataOnVolumes:] : 960 -> 936
~ ___28+[SASupport getVolumesPaths]_block_invoke : 232 -> 252
~ +[SASupport getEnterpriseVolumesPaths] : 432 -> 428
~ +[SASupport shouldExcludeCacheSizeForBundle:] : 320 -> 316
~ ___31+[SASupport getRelevantVolumes]_block_invoke : 420 -> 416
~ +[SAUtilities processArrayConcurrently:number:queue:group:block:] : 528 -> 524
~ ___65+[SAUtilities processArrayConcurrently:number:queue:group:block:]_block_invoke : 268 -> 264
~ ___39+[SAReporter collectSAFAppSizeResults:]_block_invoke : 2632 -> 2616
~ -[SAAppSizeBreakdown addPath:fixedPath:size:] : 164 -> 160
~ -[SAPathManager checkUnAllowedBundleIDs:] : 556 -> 552
~ -[SAPathManager checkForDuplicatePathsWithDifferentExclusivity:] : 700 -> 696
~ -[SAPathManager validatePaths:] : 328 -> 324
~ -[SAPathManager registerPaths:forBundleID:completionHandler:] : 372 -> 368
~ -[SAPathManager unregisterURLs:forBundleID:completionHandler:] : 372 -> 368
~ -[SAAppSizerResults print] : 772 -> 760
~ -[SAAppSizerResults zeroSizeAppsFiltering] : 452 -> 448
~ -[SAAppSizerResults postProcessFilteringWithAppPathList:] : 1840 -> 1844
~ -[SAAppSizerResults postProcessMerging] : 968 -> 960
~ ___43+[SAInternalAPI getAppPathsWithReplyBlock:]_block_invoke_3 : 448 -> 444
```
