## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f848` | `0x180ce0` | **`+0x1498`** |
| `__AUTH_CONST.__cfstring` | `0xc000` | `0xc280` | **`+0x280`** |
| `__TEXT.__cstring` | `0xd240` | `0xd3e0` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0xf978` | `0xfae0` | **`+0x168`** |
| `__AUTH_CONST.__objc_const` | `0x2c388` | `0x2c4d0` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x1b9a4` | `0x1bae4` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x7f27` | `0x8027` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x120d8` | `0x12180` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x9000` | `0x90a8` | **`+0xa8`** |
| `__DATA.__data` | `0x68d8` | `0x6938` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x7740` | `0x7770` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x25e8` | `0x2618` | **`+0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x4e0` | `0x4f8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1418` | `0x1428` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1f00` | `0x1f10` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x580` | `0x588` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x8e0` | `0x8e8` | **`+0x8`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Functions: 9159
-  Symbols:   17402
-  CStrings:  2513
+  Functions: 9184
+  Symbols:   17446
+  CStrings:  2535
Symbols:
+ -[SFBarRegistration layout]
+ -[SFBarRegistration persona]
+ -[SFPageZoomStepperController currentPercentageText]
+ -[SFUnifiedBarRegistration persona]
+ -[SFWebViewController canAutoFillNewPasswordOnPageWithCompletionHandler:]
+ -[SFWebViewController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]
+ -[_SFBrowserContentViewController automaticPasswordChangeController:canAutoFillNewPasswordOnPageWithCompletionHandler:]
+ -[_SFBrowserContentViewController pageZoomFactor]
+ -[_SFDownload previewItemTitle]
+ -[_SFDownload previewItemURL]
+ -[_SFFormAutoFillController _resetAutomaticPasswordChangePageLevelAutoFillStateReturningFailureIfNecessaryWithReason:]
+ -[_SFFormAutoFillController canAutoFillNewPasswordOnPageWithCompletionHandler:]
+ -[_SFFormAutoFillController didCollectFormMetadataForChangePasswordFormDetection:atURL:]
+ -[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]
+ -[_SFFormMetadataController collectFormMetadataForChangePasswordFormDetection]
+ -[_SFInjectedJavaScriptFormAutoFiller collectFormMetadataForChangePasswordFormDetectionAtURL:]
+ -[_SFPageFormatMenuController _displayStringFromRate:]
+ -[_SFPageFormatMenuController _pageZoomOptionsMenuWithCanIncrement:canDecrement:canReset:percentageText:]
+ -[_SFPageFormatMenuController _updatePageZoomOptionsWithCanIncrement:canDecrement:canReset:percentageText:]
+ -[_SFPageFormatMenuController askSiriAvailabilityDidChange]
+ -[_SFPerSitePreferencesPopoverViewController _accessibilityIdentifierForPreference:]
+ -[_SFReaderController processPendingReaderSummarizationIfNeeded]
+ -[_SFWebProcessPlugIn additionalClassesForParameterCoder]
+ -[_SFWebProcessPlugInAutoFillPageController collectFormMetadataForChangePasswordFormDetectionAtURL:]
+ GCC_except_table134
+ GCC_except_table143
+ GCC_except_table152
+ GCC_except_table162
+ GCC_except_table170
+ GCC_except_table223
+ GCC_except_table225
+ GCC_except_table227
+ GCC_except_table228
+ GCC_except_table242
+ GCC_except_table246
+ GCC_except_table259
+ GCC_except_table273
+ GCC_except_table277
+ GCC_except_table283
+ GCC_except_table288
+ GCC_except_table289
+ GCC_except_table292
+ GCC_except_table295
+ GCC_except_table302
+ GCC_except_table308
+ GCC_except_table312
+ GCC_except_table313
+ GCC_except_table320
+ GCC_except_table324
+ GCC_except_table325
+ GCC_except_table332
+ GCC_except_table336
+ GCC_except_table339
+ GCC_except_table343
+ GCC_except_table351
+ GCC_except_table357
+ GCC_except_table358
+ GCC_except_table369
+ GCC_except_table370
+ GCC_except_table379
+ GCC_except_table382
+ GCC_except_table391
+ GCC_except_table392
+ GCC_except_table397
+ GCC_except_table400
+ GCC_except_table403
+ GCC_except_table415
+ GCC_except_table418
+ GCC_except_table424
+ GCC_except_table440
+ GCC_except_table441
+ GCC_except_table453
+ GCC_except_table454
+ GCC_except_table461
+ GCC_except_table464
+ GCC_except_table472
+ GCC_except_table482
+ GCC_except_table491
+ GCC_except_table505
+ GCC_except_table516
+ GCC_except_table517
+ GCC_except_table522
+ GCC_except_table523
+ GCC_except_table526
+ GCC_except_table527
+ GCC_except_table534
+ GCC_except_table535
+ GCC_except_table541
+ GCC_except_table544
+ GCC_except_table545
+ GCC_except_table551
+ GCC_except_table552
+ GCC_except_table556
+ GCC_except_table557
+ GCC_except_table571
+ GCC_except_table578
+ GCC_except_table584
+ GCC_except_table587
+ GCC_except_table588
+ GCC_except_table596
+ GCC_except_table603
+ GCC_except_table604
+ GCC_except_table611
+ GCC_except_table617
+ GCC_except_table622
+ GCC_except_table626
+ GCC_except_table631
+ GCC_except_table635
+ GCC_except_table638
+ GCC_except_table642
+ GCC_except_table647
+ GCC_except_table648
+ GCC_except_table654
+ GCC_except_table659
+ GCC_except_table666
+ GCC_except_table667
+ GCC_except_table668
+ _OBJC_CLASS_$_SFBrowsingAssistantFavoritedMenuActionsStore
+ _OBJC_CLASS_$_SFEnhancedSiriAvailabilityMonitor
+ _OBJC_CLASS_$_WBSAutoFillValuesResult
+ _OBJC_IVAR_$_SFBarRegistration._persona
+ _OBJC_IVAR_$__SFBrowserContentViewController._enhancedSiriAvailabilityMonitor
+ _OBJC_IVAR_$__SFFormAutoFillController._pendingChangePasswordFormDetectionCompletionHandlers
+ _OBJC_IVAR_$__SFPageFormatMenuController._favoritedMenuActionsStore
+ _SFBrowsingAssistantMenuSectionIdentifierEditPrivacyAndSecurityActions
+ _SFBrowsingAssistantMenuSectionIdentifierEditTabActions
+ _SFBrowsingAssistantMenuSectionIdentifierIntelligence
+ _SFDefaultActionsMenuFavoritedActions
+ _WBSShouldDisplayRecentSearchesInStartPageKey
+ __OBJC_$_PROP_LIST_QLPreviewItem
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_QLPreviewItem
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_QLPreviewItem
+ __OBJC_$_PROTOCOL_METHOD_TYPES_QLPreviewItem
+ __OBJC_$_PROTOCOL_REFS_QLPreviewItem
+ __OBJC_LABEL_PROTOCOL_$_QLPreviewItem
+ __OBJC_PROTOCOL_$_QLPreviewItem
+ __ZNSt3__119__shared_weak_count16__release_sharedB9sqe220106Ev
+ ___107-[_SFPageFormatMenuController _updatePageZoomOptionsWithCanIncrement:canDecrement:canReset:percentageText:]_block_invoke
+ ___107-[_SFPageFormatMenuController _updatePageZoomOptionsWithCanIncrement:canDecrement:canReset:percentageText:]_block_invoke_2
+ ___159-[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]_block_invoke
+ ___159-[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:watchdogTimeout:completionHandler:]_block_invoke_2
+ ___58-[_SFBrowserContentViewController initWithNibName:bundle:]_block_invoke_3
+ ___59-[_SFPageFormatMenuController askSiriAvailabilityDidChange]_block_invoke
+ ___61-[_SFPageFormatMenuController _listenToPagePlaybackSpeedMenu]_block_invoke_4
+ ___64-[_SFReaderController processPendingReaderSummarizationIfNeeded]_block_invoke
+ ___78-[_SFFormMetadataController collectFormMetadataForChangePasswordFormDetection]_block_invoke
+ ___79-[_SFFormAutoFillController canAutoFillNewPasswordOnPageWithCompletionHandler:]_block_invoke
+ ___94-[_SFInjectedJavaScriptFormAutoFiller collectFormMetadataForChangePasswordFormDetectionAtURL:]_block_invoke
+ ___block_descriptor_121_e8_32s40s48s56s64s72s80s88r96r104r_e5_v8?0lr88l8s32l8r96l8s40l8s48l8s56l8s64l8s72l8s80l8r104l8
+ ___block_descriptor_40_e8_32w_e24_"UIMenu"16?0"UIMenu"8lw32l8
+ ___block_descriptor_48_ea8_32bs40r_e33_v16?0"WBSAutoFillValuesResult"8lr40l8s32l8
+ ___block_descriptor_51_e8_32s40s_e24_"UIMenu"16?0"UIMenu"8ls32l8s40l8
+ ___block_descriptor_56_ea8_32bs40r_e5_v8?0lr40l8s32l8
+ _showRecentSearchesDefaultsKey
- -[SFWebViewController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:completionHandler:]
- -[_SFFormAutoFillController _resetAutomaticPasswordChangePageLevelAutoFillState]
- -[_SFFormAutoFillController performPageLevelAutoFillWithoutAuthentication:options:generatedPassword:earliestOneTimeCodeDate:completionHandler:]
- -[_SFPageFormatMenuController _pageZoomOptionsMenuWithCanIncrement:canDecrement:percentageText:]
- -[_SFPageFormatMenuController _updatePageZoomOptionsWithCanIncrement:canDecrement:percentageText:]
- -[_SFSettingsAlertItem isFavorited]
- -[_SFSettingsAlertItem setFavorited:]
- GCC_except_table135
- GCC_except_table144
- GCC_except_table153
- GCC_except_table158
- GCC_except_table167
- GCC_except_table171
- GCC_except_table198
- GCC_except_table215
- GCC_except_table232
- GCC_except_table237
- GCC_except_table239
- GCC_except_table261
- GCC_except_table266
- GCC_except_table268
- GCC_except_table275
- GCC_except_table279
- GCC_except_table285
- GCC_except_table290
- GCC_except_table291
- GCC_except_table296
- GCC_except_table305
- GCC_except_table306
- GCC_except_table310
- GCC_except_table314
- GCC_except_table317
- GCC_except_table322
- GCC_except_table328
- GCC_except_table334
- GCC_except_table335
- GCC_except_table341
- GCC_except_table345
- GCC_except_table348
- GCC_except_table353
- GCC_except_table366
- GCC_except_table367
- GCC_except_table372
- GCC_except_table377
- GCC_except_table381
- GCC_except_table384
- GCC_except_table393
- GCC_except_table394
- GCC_except_table399
- GCC_except_table413
- GCC_except_table416
- GCC_except_table419
- GCC_except_table420
- GCC_except_table426
- GCC_except_table445
- GCC_except_table452
- GCC_except_table457
- GCC_except_table460
- GCC_except_table470
- GCC_except_table480
- GCC_except_table487
- GCC_except_table503
- GCC_except_table514
- GCC_except_table515
- GCC_except_table520
- GCC_except_table521
- GCC_except_table524
- GCC_except_table525
- GCC_except_table529
- GCC_except_table530
- GCC_except_table539
- GCC_except_table540
- GCC_except_table543
- GCC_except_table546
- GCC_except_table549
- GCC_except_table554
- GCC_except_table555
- GCC_except_table565
- GCC_except_table572
- GCC_except_table579
- GCC_except_table582
- GCC_except_table586
- GCC_except_table592
- GCC_except_table597
- GCC_except_table600
- GCC_except_table609
- GCC_except_table615
- GCC_except_table618
- GCC_except_table624
- GCC_except_table625
- GCC_except_table632
- GCC_except_table633
- GCC_except_table637
- GCC_except_table640
- GCC_except_table646
- GCC_except_table651
- GCC_except_table652
- GCC_except_table656
- GCC_except_table663
- _OBJC_CLASS_$_UIDeferredMenuElement
- _OUTLINED_FUNCTION_93
- __ZNSt3__119__shared_weak_count16__release_sharedB9sqe220100Ev
- ___96-[_SFPageFormatMenuController _pageZoomOptionsMenuWithCanIncrement:canDecrement:percentageText:]_block_invoke
- ___96-[_SFPageFormatMenuController _pageZoomOptionsMenuWithCanIncrement:canDecrement:percentageText:]_block_invoke_2
- ___98-[_SFPageFormatMenuController _updatePageZoomOptionsWithCanIncrement:canDecrement:percentageText:]_block_invoke
- ___98-[_SFPageFormatMenuController _updatePageZoomOptionsWithCanIncrement:canDecrement:percentageText:]_block_invoke_2
- ___block_descriptor_121_e8_32s40s48s56s64s72s80s88r96r104r_e5_v8?0lr88l8s32l8s40l8r96l8s48l8s56l8s64l8s72l8s80l8r104l8
- ___block_descriptor_48_e8_32s40bs_e14_v20?0B8B12B16ls32l8s40l8
- ___block_descriptor_48_e8_32s40w_e24_v16?0?<v?"NSArray">8lw40l8s32l8
- ___block_descriptor_50_e8_32s40s_e24_"UIMenu"16?0"UIMenu"8ls32l8s40l8
CStrings:
+ "CameraPreferencePopUpCell"
+ "Cannot generate a strong password: no credential providers support saving."
+ "CustomizeMenu"
+ "CustomizeMenuButton"
+ "Failed to extract reader text for deferred summarization: %@"
+ "GeolocationPreferencePopUpCell"
+ "Internal"
+ "ListenToPagePlayPause"
+ "ListenToPageSkipBackward"
+ "ListenToPageSkipForward"
+ "MicrophonePreferencePopUpCell"
+ "Page-level AutoFill watchdog fired after %f seconds; failing the request."
+ "PageMenuDoneButton"
+ "Reader text for deferred summarization was empty"
+ "ReaderPreferenceSwitchCell"
+ "RequestDesktopSitePreferenceSwitchCell"
+ "Secure Connection"
+ "SelectedSpeakingRate?rate=%@"
+ "ShowRecentSearches"
+ "WBSSearchProvider"
+ "hammer"
+ "lock.badge.checkmark"
+ "safariActionsMenu"
+ "shield.lefthalf.filled.badge.checkmark"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xe1"
+ "\xf0\xf2"
- "v16@?0@?<v@?@\"NSArray\">8"
- "v20@?0B8B12B16"
- "\xf0\xe2"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xc1"
```
