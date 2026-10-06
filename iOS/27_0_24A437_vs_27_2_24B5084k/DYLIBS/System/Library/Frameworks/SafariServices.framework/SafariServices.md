## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x183bc0` | `0x1856c8` | **`+0x1b08`** |
| `__AUTH_CONST.__cfstring` | `0xc3e0` | `0xc640` | **`+0x260`** |
| `__TEXT.__gcc_except_tab` | `0xfc84` | `0xfe5c` | **`+0x1d8`** |
| `__TEXT.__cstring` | `0xd470` | `0xd640` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x81d7` | `0x83a7` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x1bd4c` | `0x1bdbc` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x12328` | `0x12390` | **`+0x68`** |
| `__DATA.__data` | `0x69b0` | `0x6950` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x2c6a8` | `0x2c700` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x9210` | `0x9268` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x2220` | `0x2270` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1488` | `0x14a8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x588` | `0x5a8` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x47c` | `0x49c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2710` | `0x2728` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1f24` | `0x1f34` | **`+0x10`** |
| `__TEXT.__const` | `0x2eb4` | `0x2ec4` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x8e8` | `0x8e0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x6ac` | `0x6b0` | **`+0x4`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 9284
-  Symbols:   17525
-  CStrings:  2549
+  Functions: 9308
+  Symbols:   17546
+  CStrings:  2573
Symbols:
+ -[SFWebViewController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:staleOneTimeCodeThresholdDate:watchdogTimeout:completionHandler:]
+ -[_SFBrowserContentViewController _automaticPasswordChangeInitialLoadDidFailWithError:]
+ -[_SFBrowserContentViewController _logAutomaticPasswordChangeNavigationMilestone:navigation:error:]
+ -[_SFBrowserContentViewController _updateOverlayStateForDigitalHealthTracking:]
+ -[_SFDynamicBarAnimator synchronizedValueForHiddenValue:shownValue:]
+ -[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:staleOneTimeCodeThresholdDate:watchdogTimeout:completionHandler:]
+ -[_SFWebAppServiceViewController _guidedBrowsingReportingTabForViewController:]
+ -[_SFWebAppServiceViewController _reportBlockedGuidedBrowsingNavigationAction:isMainFrameNavigation:inViewController:]
+ -[_SFWebAppServiceViewController _reportGuidedBrowsingCurrentURLForViewController:]
+ -[_SFWebAppServiceViewController _reportGuidedBrowsingNavigationEventWithURL:httpMethod:statusCode:wasBlocked:forTab:]
+ -[_SFWebAppServiceViewController _reportGuidedBrowsingSameDocumentNavigationForViewController:]
+ -[_SFWebAppServiceViewController webViewController:decidePolicyForNavigationResponse:decisionHandler:]
+ -[_SFWebAppServiceViewController webViewController:didCommitNavigation:]
+ -[_SFWebAppServiceViewController webViewController:didSameDocumentNavigation:ofType:]
+ -[_SFWebAppTab pendingHTTPMethod]
+ -[_SFWebAppTab pendingStatusCode]
+ -[_SFWebAppTab setPendingHTTPMethod:]
+ -[_SFWebAppTab setPendingStatusCode:]
+ GCC_except_table583
+ GCC_except_table587
+ GCC_except_table590
+ GCC_except_table596
+ GCC_except_table598
+ GCC_except_table601
+ GCC_except_table606
+ GCC_except_table613
+ GCC_except_table619
+ GCC_except_table622
+ GCC_except_table624
+ GCC_except_table629
+ GCC_except_table631
+ GCC_except_table633
+ GCC_except_table638
+ GCC_except_table641
+ GCC_except_table645
+ GCC_except_table647
+ GCC_except_table650
+ GCC_except_table657
+ GCC_except_table662
+ GCC_except_table664
+ GCC_except_table671
+ GCC_except_table672
+ GCC_except_table673
+ _OBJC_CLASS_$_SFStrongPasswordGenerator
+ _OBJC_CLASS_$_WBSUsageRetentionDonationManager
+ _OBJC_IVAR_$__SFBrowserContentViewController._currentAutomaticPasswordChangeNavigationDidRenderVisibleContent
+ _OBJC_IVAR_$__SFBrowserContentViewController._hasCompletedAutomaticPasswordChangeNavigation
+ _OBJC_IVAR_$__SFFormAutoFillController._pageLevelAutoFillStaleOneTimeCodeThresholdDate
+ _OBJC_IVAR_$__SFWebAppTab._pendingHTTPMethod
+ _OBJC_IVAR_$__SFWebAppTab._pendingStatusCode
+ _WBSEnableGraphicIconsInCompletionListKey
+ _WBSEnableRecentSearchesStartPageModuleAtTopOfStartPageKey
+ ___189-[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:staleOneTimeCodeThresholdDate:watchdogTimeout:completionHandler:]_block_invoke
+ ___189-[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:staleOneTimeCodeThresholdDate:watchdogTimeout:completionHandler:]_block_invoke_2
+ ___79-[_SFBrowserContentViewController _updateOverlayStateForDigitalHealthTracking:]_block_invoke
+ ___79-[_SFBrowserContentViewController _updateOverlayStateForDigitalHealthTracking:]_block_invoke_2
+ ___block_descriptor_72_ea8_32s40s48s56bs_e28_v20?0"WBSFormMetadata"8B16ls32l8s40l8s48l8s56l8
+ _swift_isEscapingClosureAtFileLocation
+ _swift_retain_x22
+ _symbolic Ig_
- -[SFWebViewController _webView:requestPresentingViewControllerWithCompletionHandler:]
- -[SFWebViewController _webViewDidExitElementFullscreen:]
- -[SFWebViewController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]
- -[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]
- GCC_except_table116
- GCC_except_table584
- GCC_except_table588
- GCC_except_table595
- GCC_except_table597
- GCC_except_table600
- GCC_except_table602
- GCC_except_table612
- GCC_except_table618
- GCC_except_table621
- GCC_except_table623
- GCC_except_table627
- GCC_except_table630
- GCC_except_table632
- GCC_except_table635
- GCC_except_table639
- GCC_except_table642
- GCC_except_table646
- GCC_except_table648
- GCC_except_table654
- GCC_except_table658
- GCC_except_table665
- GCC_except_table667
- _OBJC_CLASS_$_SFAutoFillHelperProxy
- _OBJC_IVAR_$__SFBrowserContentViewController._hasStartedAutomaticPasswordChange
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__WKFullscreenDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES__WKFullscreenDelegate
- __OBJC_$_PROTOCOL_REFS__WKFullscreenDelegate
- __OBJC_LABEL_PROTOCOL_$__WKFullscreenDelegate
- __OBJC_PROTOCOL_$__WKFullscreenDelegate
- ___159-[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]_block_invoke
- ___159-[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]_block_invoke_2
- ___63-[_SFBrowserContentViewController _updateDigitalHealthTracking]_block_invoke_2
- ___63-[_SFBrowserContentViewController _updateDigitalHealthTracking]_block_invoke_3
- ___block_descriptor_56_ea8_32s40s48bs_e28_v20?0"WBSFormMetadata"8B16ls32l8s40l8s48l8
CStrings:
+ "&appid=aaplw_r"
+ "&enriched=1"
+ "<nil>"
+ "<none>"
+ "Failed to load change password page: %@"
+ "Initial page load did not finish within %.0f seconds, but the page rendered visible content; starting password change anyways"
+ "Initial page load failed after %.2f seconds: %{public}@"
+ "Navigating: %{public}@ at %.2fs (navigation %p, URL <%{private}@>, error %{public}@)"
+ "Navigating: decidePolicyForNavigationResponse for main frame (HTTP status %{public}ld, MIME type %{public}@, URL <%{private}@>)"
+ "Navigating: willPerformClientRedirect to <%{private}@> after %.2fs delay"
+ "com.bing.www"
+ "com.yahoo.www"
+ "didCancelClientRedirect"
+ "didCommitNavigation"
+ "didFailNavigation"
+ "didFailProvisionalNavigation"
+ "didFinishDocumentLoad"
+ "didFinishNavigation"
+ "didFirstVisuallyNonEmptyLayout"
+ "didReceiveServerRedirectForProvisionalNavigation"
+ "didStartProvisionalNavigation"
+ "loadRequest (not deferred)"
+ "loadRequest (resolved to fallback URL)"
+ "loadRequest (resolved, unchanged)"
```
