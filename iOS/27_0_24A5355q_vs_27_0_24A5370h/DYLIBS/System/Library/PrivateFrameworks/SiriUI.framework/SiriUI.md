## SiriUI

> `/System/Library/PrivateFrameworks/SiriUI.framework/SiriUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4618c` | `0x460e8` | **`-0xa4`** |

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0
Functions:
~ -[SiriUISiriStatusView _handleKeyboardDidShowNotification:] : 560 -> 556
~ -[SiriUISiriStatusView _handleKeyboardWillHideNotification:] : 396 -> 392
~ -[SiriUIContentCollectionViewCell _updateSubviewConstraints] : 1488 -> 1480
~ -[SiriUIContentCollectionViewCell prepareForReuse] : 540 -> 536
~ -[SiriUICardLoadingMonitor broadcastCardSnippet:] : 272 -> 268
~ -[SASportsEntityGroup(SiriUI) siriui_enumerateEntitiesWithGroupHandler:teamHandler:athleteHandler:] : 336 -> 332
~ -[SASportsTeam(SiriUI) siriui_enumerateEntitiesWithGroupHandler:teamHandler:athleteHandler:] : 336 -> 332
~ -[SiriUISnippetBridgeViewManager removeBridgeViewsFromView:] : 284 -> 280
~ -[SiriUIURLSession cancelAllTasksForClient:] : 248 -> 244
~ -[SiriUIReusableConfirmationFooterView setConfirmationOptions:] : 820 -> 816
~ -[SiriUIContentButton configureRoleForConfirmationOptions:] : 696 -> 692
~ ___111-[SiriUICachedUserNotificationsSettings userNotificationSettingsCenter:didUpdateNotificationSourceIdentifiers:]_block_invoke : 252 -> 248
~ -[SiriUICachedUserNotificationsSettings _currentlyObservingForAppBundleId:] : 280 -> 276
~ -[SiriUICachedUserNotificationsSettings _notifyAllObserversThatPreferencesDidChange] : 252 -> 248
~ -[SiriUICachedUserNotificationsSettings _notifyAllObserversWithAppBundleIdThatPreferencesDidChange:] : 280 -> 276
~ -[SiriUIPassThroughHitTestView hitTest:withEvent:] : 444 -> 440
~ -[SiriUICardSnippetViewController _removeShouldHideInAmbientSectionsFromCurrentCard] : 592 -> 588
~ -[SiriUICardSnippetViewController _addNextCardTo:fullCard:] : 700 -> 696
~ -[SiriUICardSnippetViewController setSnippet:] : 1676 -> 1668
~ -[SiriUICardSnippetViewController requestContext] : 952 -> 948
~ -[SiriUICardSnippetViewController performPunchoutCommand:forCardViewController:] : 776 -> 772
~ -[SiriUICardSnippetViewController cardLoader:loadCard:withCompletionHandler:] : 788 -> 784
~ -[SASendCommands(CommandUserInfo) _siriui_applyUserInfoDictionary:] : 344 -> 340
~ -[SiriUILabelStackTemplateView populateStack] : 692 -> 688
~ +[SiriUISashView _textContainerStyleForSashItem:] : 140 -> 136
~ ___67-[SiriUISnippetManager _prewarmSnippetExtensionsCacheSynchronously]_block_invoke_2 : 568 -> 564
~ -[SiriUISuggestionsView layoutSubviews] : 2472 -> 2464
~ -[SiriUICardSnippetView prepareForDrillInAnimation] : 328 -> 324
~ -[SiriUICardSnippetView prepareForPopAnimationOfType:] : 316 -> 312
~ -[SiriUIMultiNavigationTransitionController setOperation:] : 356 -> 352
~ -[SiriUIMultiNavigationTransitionController configureWithNavigationController:] : 364 -> 360
~ -[SiriUIMultiNavigationTransitionController coordinateAdditionalTransitionsWithTransitionCoordinator:] : 352 -> 348
~ -[UIView(RTL) recursive_setSemanticContentAttribute:] : 460 -> 456
~ _SiriUIBlockExecuteMonitored : 568 -> 564
~ ___71-[SiriUIAudioRoutePickerController _fetchPickableRoutesWithCompletion:]_block_invoke : 688 -> 684
~ ___84-[SiriUIAudioRoutePickerController _showAlertControllerFromViewController:animated:]_block_invoke : 944 -> 940
~ -[SiriUITemplatedStackSnippetView desiredHeight] : 312 -> 308
~ -[SADecoratedString(SiriUI) siriui_enumeratePropertyRangesUsingBlock:] : 332 -> 328
```
