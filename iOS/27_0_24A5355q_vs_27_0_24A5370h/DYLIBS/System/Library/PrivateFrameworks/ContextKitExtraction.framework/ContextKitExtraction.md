## ContextKitExtraction

> `/System/Library/PrivateFrameworks/ContextKitExtraction.framework/ContextKitExtraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd85c` | `0xd840` | **`-0x1c`** |

### Other Changes

```text
Functions:
~ ___72-[CKContextContentProviderManager _hasForegroundActiveContentWithReply:]_block_invoke : 396 -> 392
~ -[CKContextContentProviderManager _prepareDonationWithNonce:options:isRecentsCapture:andReply:] : 1188 -> 1180
~ +[CKContextContentProviderUIScene extractFromScene:usingExecutor:withOptions:] : 476 -> 472
~ +[CKContextContentProviderUIScene _donateContentsOfWindow:usingExecutor:withOptions:] : 1652 -> 1644
~ +[CKContextContentProviderUIScene _descendantsRelevantForContentExtractionFromWindow:] : 632 -> 628
~ +[CKContextContentProviderUIScene _descendantsRelevantForContentExtractionFromView:intoArray:] : 452 -> 448
~ +[CKContextContentProviderUIScene _bestVisibleStringForView:usingExecutor:] : 1992 -> 1988
~ +[CKContextContentProviderUIScene _allViewControllersFromUIViews:] : 328 -> 324
~ +[CKContextContentProviderUIScene _extractItemsFromViewControllers:] : 1616 -> 1604
~ +[CKContextSharedExtractionHelper textBlockLooksLikeAListWithText:] : 528 -> 524
~ +[CKContextSharedExtractionHelper descendantsRelevantForContentExtractionFromView:intoArray:] : 452 -> 448
~ +[CKContextSharedExtractionHelper bestContentStringForWebViewUIElements:andTitle:] : 504 -> 500
~ +[CKContextContentProviderUIScene _UIElementsForWebViewContentString:] : 632 -> 628
~ +[CKContextContentProviderUIScene _bestContentStringForWebViewUIElements:andTitle:] : 504 -> 500
~ ___192+[CKContextContentProviderUIScene _extractContentFromWebView:includingSnapshot:includingUIBoundingBox:ignoreViewTextLengthRequirements:ignoreViewCountCap:includeRawHTML:withCompletionHandler:]_block_invoke_2 : 1892 -> 1908
~ -[CKContextContentProviderUIScene _containerViewForDebugButtons] : 596 -> 592
~ -[CKContextContentProviderUIScene _descendantsRelevantForDebugControls:] : 476 -> 472
~ +[CKContextContentProviderComponent _donateContentsOfParentView:usingExecutor:withOptions:] : 1460 -> 1488
~ +[CKContextContentProviderComponent _decendantsRelevantForExtractionFromParentView:] : 632 -> 628
~ +[CKContextContentProviderComponent _UIElementsForWebViewContentString:withSceneIdentifier:] : 684 -> 680
~ ___109+[CKContextContentProviderComponent _extractContentFromWebView:includingUIBoundingBox:withCompletionHandler:]_block_invoke.159 -> ___109+[CKContextContentProviderComponent _extractContentFromWebView:includingUIBoundingBox:withCompletionHandler:]_block_invoke.174 : 1924 -> 1940
```
