## DocumentManager

> `/System/Library/PrivateFrameworks/DocumentManager.framework/DocumentManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x339d4` | `0x33944` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x33b0` | `0x33c8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x4de7` | `0x4dde` | **`-0x9`** |

### Other Changes

```diff

-389.2.0.0.0
+392.0.0.0.0

-  Functions: 1250
+  Functions: 1251
Functions:
~ -[UIDocumentBrowserViewController initForOpeningContentTypes:] : 456 -> 452
~ -[UIDocumentBrowserViewController viewDidLoad] : 240 -> 272
~ -[UIDocumentBrowserViewController _clearShownViewControllers] : 288 -> 284
~ -[DOCUserInterfaceStateStore _loadUserInterfaceStateFromDefaultsForConfiguration:] : 1064 -> 1068
~ -[DOCUserInterfaceStateStore _writeUserInterfaceStateToDefaultsForConfiguration:] : 920 -> 916
~ -[DOCUserInterfaceStateStore _pruneOldState] : 1056 -> 1048
~ +[DOCUISession(DOCDeprecatedAPI) windowWithRootViewController:] : 328 -> 324
~ -[UIDocumentBrowserViewController setAdditionalLeadingNavigationBarButtonItems:] : 692 -> 688
~ -[UIDocumentBrowserViewController setAdditionalTrailingNavigationBarButtonItems:] : 692 -> 688
~ ___94-[UIDocumentBrowserViewController prepareItemBookmarks:forMode:usingBookmark:completionBlock:]_block_invoke : 664 -> 672
~ -[UIDocumentBrowserViewController getTrackingViews:remoteButtons:fromBarButtons:] : 712 -> 692
~ -[UIDocumentBrowserViewController trackingViewForUUID:] : 396 -> 392
~ -[UIDocumentBrowserViewController remoteBarButtonForUUID:] : 396 -> 392
~ -[UIDocumentBrowserViewController _activityViewControllerWithItemBookmarks:isForTitleMenuFolderSharing:popoverTracker:isContentManaged:additionalActivities:activityRunner:] : 1840 -> 1832
~ ___172-[UIDocumentBrowserViewController _activityViewControllerWithItemBookmarks:isForTitleMenuFolderSharing:popoverTracker:isContentManaged:additionalActivities:activityRunner:]_block_invoke : 280 -> 276
~ ___57-[UIDocumentBrowserViewController _didPickItemBookmarks:]_block_invoke : 584 -> 580
~ ___79-[UIDocumentBrowserViewController _didTriggerBarButtonWithUUID:overflowAction:]_block_invoke : 808 -> 804
~ -[UISheetPresentationController(DOCUIPDocumentLandingMode) doc_documentLandingModeForDetent:] : 324 -> 320
~ +[DOCKeyboardFocusManager _applySystemOverridePriority:] : 240 -> 236
~ -[DOCKeyboardFocusManager adjacentFocusableToFocusable:direction:] : 656 -> 648
~ +[DOCRemoteViewController instantiateRemoteViewControllerWithConfiguration:transparent:errorHandler:hostProxy:completionHandler:] : 636 -> 632
~ +[DOCDocumentSource(SearchInternal) defaultSourceForBundleIdentifier:defaultSourceIdentifier:sources:] : 1640 -> 1628
~ -[DOCRemoteUIBarButtonItemRegistry barButtonItemPresentedInNavigationBar:uuid:] : 376 -> 372
~ ___74-[DOCSmartFolderDatabase registerFilenameHit:fileTypeHit:smartScoreBlock:]_block_invoke : 628 -> 624
+ _OUTLINED_FUNCTION_10
~ -[DOCKeyCommandController buildWithBuilder:] : 2176 -> 2164
~ -[DOCKeyCommandController _keyCommandsInMenu:] : 420 -> 416
~ -[DOCKeyCommandController allKeyCommands] : 508 -> 504
~ -[DOCKeyCommandController allKeyCommandsWithAction:attributes:] : 356 -> 352
~ +[DOCItemBookmark documentsURLsForItemBookmarks:] : 348 -> 344
~ +[DOCItemBookmark isAnyItemBookmarkAFault:] : 308 -> 304
~ +[DOCItemBookmark isAnyNodeAFault:] : 276 -> 272
~ -[DOCDocumentSource isValidForConfiguration:] : 516 -> 512
~ -[DOCAppearance horizontalTableStackSpacingForWindow:traits:] : 128 -> 124
~ -[DOCIconService _loadIconsFromDiskForSize:fileManager:] : 1272 -> 1268
~ -[DOCIconService _persistCacheForSize:bundles:fileManager:] : 1380 -> 1376
~ -[DOCIconService _updateFileProvidersIcon:skipSize:] : 460 -> 456
~ -[DOCActivity canPerformWithActivityItems:] : 292 -> 288
~ -[DOCActivity performActivity] : 632 -> 628
~ -[DOCUserInterfaceStateStore _loadUserInterfaceStateFromDefaultsForConfiguration:].cold.2 : 172 -> 160
~ -[DOCUserInterfaceStateStore _writeUserInterfaceStateToDefaultsForConfiguration:].cold.2 : 172 -> 160
CStrings:
+ "%s: Decoded saved state for %ld identifiers %{public}@ from defaults"
+ "%s: Unable to unarchive state for id: %{public}@ error: %@"
+ "%s: Unarchived state for id: %{public}@ error: %@"
+ "person.2"
- "%s: Decoded saved state for %ld identifiers %@ from defaults"
- "%s: Unable to unarchive state for id: %@ error: %@"
- "%s: Unarchived state for id: %@ error: %@"
- "folder.and.person"
```
