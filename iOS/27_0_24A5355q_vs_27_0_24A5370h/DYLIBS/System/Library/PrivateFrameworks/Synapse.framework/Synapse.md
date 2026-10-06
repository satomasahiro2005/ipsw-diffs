## Synapse

> `/System/Library/PrivateFrameworks/Synapse.framework/Synapse`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37ae8` | `0x37a5c` | **`-0x8c`** |

### Other Changes

```text
Functions:
~ -[NSUserActivity(SynapseExtensions) set_canonicalURL:] : 592 -> 588
~ ___73+[SYItemIndexingManager fetchIdentifiersLinkedToUserActivity:completion:]_block_invoke : 612 -> 608
~ -[SYBacklinkMonitorFilterCacheOperation _updateBacklinkFilterCacheWithInfos:] : 544 -> 540
~ +[SYContentItemPreviewManager loadPreviewDataForItems:fullDetail:didFinishLoadingPreviewHandler:] : 528 -> 524
~ ___52-[SYAddLinkContextClient userDidRemoveContentItems:]_block_invoke_2 : 756 -> 752
~ ___53-[SYAddLinkContextClient userEditDidAddContentItems:]_block_invoke_2 : 756 -> 752
~ +[SYDocumentFetchRequest _buildResultWithMatches:] : 584 -> 580
~ ___73-[SYDocumentSenderAvatar fetchThumbnailImagesWithScale:isRTL:completion:]_block_invoke_2 : 1148 -> 1144
~ -[SYDocumentSenderAvatar _documentSenderHandle] : 432 -> 428
~ -[SYDocumentSenderAvatar fetchThumbnailImagesWithScale:isRTL:] : 860 -> 856
~ -[NSData(SynapseExtensions) _sy_containsUnsignedShort:inRange:] : 180 -> 184
~ ___87-[SYLinkableContentItemFinder fetchLinkableContentItemsExcludingActivities:completion:]_block_invoke_2 : 1368 -> 1364
~ ___86-[SYLinkableContentItemFinder _fetchActiveLinkableUserActivitiesExcluding:completion:]_block_invoke.24 : 1196 -> 1188
~ -[SYLinkableContentItemFinder _shouldIncludeAsLinkableUserActivity:bundleID:foregroundBundleIDs:excludedActivities:] : 432 -> 428
~ -[SYLinkableContentItemFinder _activityFetchingFinishedWithActivities:appBundleIDs:foregroundBundleIDs:completion:] : 724 -> 712
~ -[SYLinkableContentItemFinder _updateForegroundAppsFromDisplayLayout:] : 460 -> 456
~ -[SYLinkContextClient _linkContextDictionariesFromDataArray:error:] : 676 -> 684
~ -[SYLinkContextClient userDidRemoveContentItemDatas:] : 420 -> 416
~ -[SYLinkContextClient userEditDidAddContentItemDatas:] : 420 -> 416
~ -[SYLinkContextClient _invalidateConnection] : 972 -> 964
~ ___90-[SYDocumentWorkflowsActivityChangeHandler handleActiveUserActivityChange:withCompletion:]_block_invoke.9 : 1012 -> 1008
~ ___65-[SYNotesActivationCommand _loadDataFromFileURLs:withCompletion:]_block_invoke : 520 -> 516
~ ___76+[SYItemIndexingManager _fetchIndexedActivitiesWithActivityType:completion:]_block_invoke : 320 -> 316
~ ___73+[SYItemIndexingManager fetchLinkContextsDataForUserActivity:completion:]_block_invoke : 444 -> 440
~ +[SYItemIndexingManager _postFilteredItems:matchingUserActivityInfo:] : 460 -> 456
~ -[SYBacklinkMonitorClient _invalidateConnection] : 560 -> 556
~ +[SYDocumentAttributesFetchRequest _buildResultWithMatches:] : 1068 -> 1052
~ ___72-[SYDocumentWorkflowsServiceHandle updateLinkedDocumentsWithCompletion:]_block_invoke.33 : 972 -> 968
~ ___91-[SYDocumentWorkflowsServiceHandle unlinkDocumentsWithRelatedUniqueIdentifiers:completion:]_block_invoke_2 : 908 -> 896
~ +[SYLastModifiedDocumentFetchRequest _buildResultWithMatches:] : 760 -> 756
~ _SYCanUseObjectInContextInfo : 324 -> 320
```
