## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x181134` | `0x1838e4` | **`+0x27b0`** |
| `__DATA.__bss` | `0x710` | `0xb90` | **`+0x480`** |
| `__TEXT.__const` | `0x2b74` | `0x2eb4` | **`+0x340`** |
| `__AUTH_CONST.__objc_const` | `0x2c4c0` | `0x2c618` | **`+0x158`** |
| `__TEXT.__objc_methlist` | `0x1bb44` | `0x1bc9c` | **`+0x158`** |
| `__AUTH_CONST.__cfstring` | `0xc2e0` | `0xc400` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x90c8` | `0x91e8` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x80c7` | `0x81d7` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x5b8` | `0x6ac` | **`+0xf4`** |
| `__AUTH_CONST.__const` | `0x2110` | `0x2200` | **`+0xf0`** |
| `__TEXT.__ustring` | `0x36f6` | `0x37d2` | **`+0xdc`** |
| `__DATA_CONST.__objc_selrefs` | `0x121c0` | `0x12290` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x1138` | `0x1208` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0xfb74` | `0xfc30` | **`+0xbc`** |
| `__TEXT.__constg_swiftt` | `0x1a4` | `0x218` | **`+0x74`** |
| `__DATA.__data` | `0x6948` | `0x69b0` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x1428` | `0x1488` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x7780` | `0x77d0` | **`+0x50`** |
| `__TEXT.__cstring` | `0xd400` | `0xd450` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `—` | `0x48` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x440` | `0x47c` | **`+0x3c`** |
| `__AUTH_CONST.__objc_intobj` | `0xc78` | `0xca8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xd8` | `0x108` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x120` | `0x148` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x4` | `0x28` | **`+0x24`** |
| `__DATA.__objc_ivar` | `0x1f0c` | `0x1f24` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__AUTH.__objc_data` | `0x5e88` | `0x5e98` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xf0` | `0xfc` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x70` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x7c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x24` | **`+0x8`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 9188
-  Symbols:   17444
-  CStrings:  2536
+  Functions: 9273
+  Symbols:   17504
+  CStrings:  2549
Symbols:
+ -[SFBarRegistration pageFormatCustomView]
+ -[SFBarRegistration setPageFormatCustomView:]
+ -[SFBrowserServiceViewController _URLWillOpenHostApp:]
+ -[SFBrowserServiceViewController _openURLInHostAppIfPossible:]
+ -[SFFormAutocompleteState _textSuggestionForESimDataType:]
+ -[SFPasswordPickerServiceViewController _fillOneTimeCode:]
+ -[SFWebExtensionPageMenuController iconForMenuActionWithTab:]
+ -[_SFAutomaticPasswordInputViewController _completeFillWithPassword:]
+ -[_SFAutomaticPasswordInputViewController passwordSavingViewController:didFinishWithError:completion:]
+ -[_SFAutomaticPasswordInputViewController presentUIForPasswordSavingViewController:]
+ -[_SFBrowserContentViewController _URLWillOpenHostApp:]
+ -[_SFBrowserContentViewController _openURLInHostAppIfPossible:]
+ -[_SFBrowserContentViewController toolbarLayout]
+ -[_SFFormAutoFillController didCommitNavigation:]
+ -[_SFLinkPreviewHelper openInNewTabActionForURL:withTabOrder:preActionHandler:openToSide:]
+ -[_SFNavigationBar borrowPageFormatButton]
+ -[_SFNavigationBar returnPageFormatButton]
+ -[_SFReaderController reportSummaryFeedback:]
+ -[_SFReaderWebProcessPlugInPageController reportSummaryFeedback:]
+ -[_SFWebAppServiceViewController _dismissGuidedBrowsingActionBlockedNoticeIfNecessary]
+ -[_SFWebAppServiceViewController scrollEdgeEffectStyle]
+ -[_SFWebAppServiceViewController showGuidedBrowsingActionBlockedNoticeWithMessage:]
+ -[_SFWebAppServiceViewController showGuidedBrowsingNewWindowBlockedNotice]
+ -[_SFWebAppViewController showGuidedBrowsingNewWindowBlockedNotice]
+ GCC_except_table130
+ GCC_except_table140
+ GCC_except_table143
+ GCC_except_table149
+ GCC_except_table151
+ GCC_except_table162
+ GCC_except_table168
+ GCC_except_table170
+ GCC_except_table205
+ GCC_except_table218
+ GCC_except_table219
+ GCC_except_table236
+ GCC_except_table261
+ GCC_except_table271
+ GCC_except_table275
+ GCC_except_table276
+ GCC_except_table279
+ GCC_except_table288
+ GCC_except_table293
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
+ GCC_except_table441
+ GCC_except_table442
+ GCC_except_table454
+ GCC_except_table455
+ GCC_except_table462
+ GCC_except_table465
+ GCC_except_table473
+ GCC_except_table483
+ GCC_except_table492
+ GCC_except_table506
+ GCC_except_table517
+ GCC_except_table518
+ GCC_except_table523
+ GCC_except_table524
+ GCC_except_table527
+ GCC_except_table528
+ GCC_except_table535
+ GCC_except_table536
+ GCC_except_table542
+ GCC_except_table545
+ GCC_except_table546
+ GCC_except_table552
+ GCC_except_table553
+ GCC_except_table557
+ GCC_except_table558
+ GCC_except_table572
+ GCC_except_table579
+ GCC_except_table585
+ GCC_except_table588
+ GCC_except_table589
+ GCC_except_table597
+ GCC_except_table604
+ GCC_except_table605
+ GCC_except_table612
+ GCC_except_table618
+ GCC_except_table623
+ GCC_except_table627
+ GCC_except_table632
+ GCC_except_table636
+ GCC_except_table639
+ GCC_except_table643
+ GCC_except_table648
+ GCC_except_table649
+ GCC_except_table655
+ GCC_except_table660
+ GCC_except_table668
+ GCC_except_table669
+ _ASCAuthorizationErrorDomain
+ _OBJC_CLASS_$_ASCAgentProxy
+ _OBJC_IVAR_$_SFBarRegistration._cancelItem
+ _OBJC_IVAR_$_SFBarRegistration._pageFormatCustomView
+ _OBJC_IVAR_$_SFBarRegistration._pageFormatItem
+ _OBJC_IVAR_$__SFAutomaticPasswordInputViewController._generatedPasswordFilledViewController
+ _OBJC_IVAR_$__SFNavigationBar._formatToggleButtonIsBorrowed
+ _OBJC_IVAR_$__SFWebAppServiceViewController._guidedBrowsingActionBlockedNoticeMessage
+ _OBJC_IVAR_$__SFWebAppServiceViewController._guidedBrowsingActionBlockedNoticeViewController
+ _OUTLINED_FUNCTION_93
+ _SFOpenInNewTabTitleWithOpenToSide
+ _WBSDeviceIMEI1ClassificationToken
+ _WBSDeviceIMEI2ClassificationToken
+ _WBSDeviceNALClassificationToken
+ __ZL26localAuthenticationOptionsP8NSStringS0_S0_
+ __ZN14SafariServices34WebProcessPlugInReaderJSController21reportSummaryFeedbackE21WBSUserReportedAction
+ ___102-[_SFAutomaticPasswordInputViewController passwordSavingViewController:didFinishWithError:completion:]_block_invoke
+ ___58-[SFPasswordPickerServiceViewController _fillOneTimeCode:]_block_invoke
+ ___58-[SFPasswordPickerServiceViewController _fillOneTimeCode:]_block_invoke_2
+ ___58-[SFPasswordPickerServiceViewController _fillOneTimeCode:]_block_invoke_3
+ ___90-[_SFLinkPreviewHelper openInNewTabActionForURL:withTabOrder:preActionHandler:openToSide:]_block_invoke
+ ___block_descriptor_48_ea8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
+ ___swift_closure_destructor.10Tm
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation021_ObjectiveCBridgeableB0SCs0B0
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation13CustomNSErrorSCs0B0
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation21_BridgedStoredNSErrorSC4CodeAcDP_8RawValueSYs17FixedWidthInteger
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation21_BridgedStoredNSErrorSC4CodeAcDP_AC01_bG8Protocol
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation21_BridgedStoredNSErrorSC4CodeAcDP_SY
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation21_BridgedStoredNSErrorSCAC021_ObjectiveCBridgeableB0
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation21_BridgedStoredNSErrorSCAC06CustomF0
+ _associated conformance SC21ASCAuthorizationErrorLeV10Foundation21_BridgedStoredNSErrorSCSH
+ _associated conformance SC21ASCAuthorizationErrorLeVSHSCSQ
+ _associated conformance So21ASCAuthorizationErrorV10Foundation01_B12CodeProtocolSC01_B4TypeAcDP_AC21_BridgedStoredNSError
+ _associated conformance So21ASCAuthorizationErrorV10Foundation01_B12CodeProtocolSCSQ
+ _classificationTokenForESimDataType
+ _swift_getForeignTypeMetadata
+ _symbolic $s10Foundation18_ErrorCodeProtocolP
+ _symbolic $s10Foundation21_BridgedStoredNSErrorP
+ _symbolic $sSY
+ _symbolic SS
+ _symbolic SbSo7NSErrorCSgIeyByy_Sg
+ _symbolic SccySb______pG s5ErrorP
+ _symbolic Si
+ _symbolic So7NSErrorC
+ _symbolic _____ SC21ASCAuthorizationErrorLeV
+ _symbolic _____ So21ASCAuthorizationErrorV
+ _type_layout_string SC21ASCAuthorizationErrorLeV
- -[SFBrowserServiceViewController _willURLOpenHostApp:]
- -[_SFBrowserContentViewController _willURLOpenHostApp:]
- -[_SFFormMetadataController _checkSearchURLTemplateStringInFrame:autoFillFrame:autoFillNode:controller:]
- -[_SFFormMetadataController didFindSearchURLTemplateString:inFrame:pageController:]
- -[_SFWebAppServiceViewController _dismissGuidedBrowsingNavigationBlockedNoticeIfNecessary]
- -[_SFWebAppServiceViewController _showGuidedBrowsingNavigationBlockedNotice]
- GCC_except_table141
- GCC_except_table144
- GCC_except_table152
- GCC_except_table158
- GCC_except_table163
- GCC_except_table169
- GCC_except_table171
- GCC_except_table176
- GCC_except_table206
- GCC_except_table220
- GCC_except_table240
- GCC_except_table244
- GCC_except_table248
- GCC_except_table250
- GCC_except_table262
- GCC_except_table269
- GCC_except_table277
- GCC_except_table281
- GCC_except_table285
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
- GCC_except_table446
- GCC_except_table453
- GCC_except_table458
- GCC_except_table461
- GCC_except_table471
- GCC_except_table481
- GCC_except_table488
- GCC_except_table504
- GCC_except_table515
- GCC_except_table516
- GCC_except_table521
- GCC_except_table522
- GCC_except_table525
- GCC_except_table526
- GCC_except_table530
- GCC_except_table531
- GCC_except_table540
- GCC_except_table541
- GCC_except_table544
- GCC_except_table547
- GCC_except_table550
- GCC_except_table555
- GCC_except_table556
- GCC_except_table566
- GCC_except_table573
- GCC_except_table580
- GCC_except_table583
- GCC_except_table587
- GCC_except_table593
- GCC_except_table598
- GCC_except_table601
- GCC_except_table610
- GCC_except_table616
- GCC_except_table619
- GCC_except_table625
- GCC_except_table626
- GCC_except_table633
- GCC_except_table634
- GCC_except_table638
- GCC_except_table641
- GCC_except_table647
- GCC_except_table652
- GCC_except_table653
- GCC_except_table657
- GCC_except_table664
- _OBJC_IVAR_$__SFWebAppServiceViewController._guidedBrowsingNavigationBlockedNoticeViewController
- ___79-[_SFLinkPreviewHelper openInNewTabActionForURL:withTabOrder:preActionHandler:]_block_invoke
- ___swift_closure_destructor.8Tm
CStrings:
+ "Could not load NSExtension %{public}@ for generated-password-filled save request: %{public}@"
+ "Device identifier from CoreTelephony was empty, not showing a suggestion."
+ "Failed to get authentication to fill one-time code: %{public}@"
+ "Generated-password-filled save request failed: %{public}@"
+ "New Window Not Allowed"
+ "Open Link to Side"
+ "Skipping write to WBSGeneratedPasswordStore: no domain available for service identifier of type %ld"
+ "Your iPad’s IMEI1"
+ "Your iPad’s IMEI2"
+ "Your iPad’s NAL"
+ "Your iPhone’s IMEI1"
+ "Your iPhone’s IMEI2"
+ "Your iPhone’s NAL"
+ "com.apple.SafariServices.SFSafariSettingsError"
+ "\xf0\xf0\xf0\xa1"
- "CoreTelephonyClient does not respond to selector isAutofilleSIMIdAllowedForDomain:clientBundleIdentifier:error:"
- "\xf0\xf0\xf0\x91"
```
