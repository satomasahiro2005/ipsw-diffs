## VideoSubscriberAccountUI

> `/System/Library/PrivateFrameworks/VideoSubscriberAccountUI.framework/VideoSubscriberAccountUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62b44` | `0x6295c` | **`-0x1e8`** |

### Other Changes

```diff

-607.0.0.0.0
+608.0.0.0.0
Functions:
~ -[VSSetupFlowController _getProviderWithUserTokenFromAllProviders:] : 392 -> 388
~ -[VSViewServiceHostViewController _cancelButtonPressed:] : 304 -> 300
~ -[VSIdentityProviderSubscriptionOperation _authorizedBundleIdsFromAppDescriptions:] : 320 -> 316
~ ___116-[VSIdentityProviderSubscriptionOperation _removeSubscriptionsForBundleIdentifiers:withAuthorizedBundleIdentifiers:]_block_invoke : 996 -> 988
~ -[VSIdentityProviderSubscriptionOperation _registerSubscriptions:withAuthorizedBundleIdentifiers:] : 680 -> 676
~ ___56-[VSIdentityProviderFetchAllOperation executionDidBegin]_block_invoke : 1616 -> 1612
~ ___56-[VSIdentityProviderFetchAllOperation executionDidBegin]_block_invoke.10 : 2284 -> 2268
~ -[VSIdentityProviderFilter _camelAndWordBasedPrefixesForProvider:] : 840 -> 836
~ -[VSIdentityProviderFilter _refreshProviderList] : 844 -> 836
~ ___48-[VSIdentityProviderFilter _refreshProviderList]_block_invoke_2 : 312 -> 308
~ -[VSOnscreenCodeAuthenticationAppDocumentController _updateOnscreenCodeViewModel:withTemplate:] : 1200 -> 1196
~ -[VSOnscreenCodeViewModel websiteURLWithQueryParameters] : 812 -> 808
~ -[VSIdentityProviderViewController _showViewController:] : 436 -> 432
~ -[VSIdentityProviderViewController identityProviderRequestManager:requestsAlert:] : 1096 -> 1092
~ -[VSViewServiceRequestPreparationOperation _finishWithSupportedProviders:] : 1248 -> 1240
~ ___68-[VSViewServiceRequestPreparationOperation _checkSupportedProviders]_block_invoke : 672 -> 668
~ -[VSIdentityProviderStorefrontCollection featureProvidersInCurrentStorefront] : 520 -> 516
~ -[VSIdentityProviderStorefrontParser setAllStorefronts:withCurrentStorefrontCode:] : 500 -> 496
~ -[VSIdentityProviderStorefrontParser identityProvidersByStorefront] : 984 -> 980
~ -[VSIdentityProviderStorefrontParser tvProviderSupportedStorefronts] : 392 -> 388
~ -[VSIdentityProviderStorefrontParser providersForStorefront:featuredOnly:] : 560 -> 556
~ -[VSIdentityProviderStorefrontParser updateFeaturedStorefronts:withCurrentStorefrontCodeOrNil:] : 400 -> 396
~ -[VSAMSAllStorefrontsResponseValueTransformer transformedValue:] : 696 -> 692
~ -[VSTwoFactorEntryAppDocumentController _updateTwoFactorEntryViewModel:withTemplate:error:] : 2376 -> 2368
~ +[VSSAMLRequestFactory attributeQueryWithAttributeNames:channelID:authNResponse:error:] : 372 -> 368
~ -[VSAppSettingsViewModel applicationsWillInstall:] : 400 -> 396
~ -[VSAppSettingsViewModel applicationsDidInstall:] : 412 -> 408
~ -[VSAppSettingsViewModel applicationsDidFailToInstall:] : 400 -> 396
~ -[VSAppSettingsViewModel applicationsWillUninstall:] : 400 -> 396
~ -[VSAppSettingsViewModel applicationsDidUninstall:] : 400 -> 396
~ -[VSAppSettingsViewModel applicationsDidFailToUninstall:] : 400 -> 396
~ -[VSAutoAuthenticationAppDocumentController _updateAutoAuthenticationViewModel:withTemplate:] : 1140 -> 1136
~ -[VSTwoFactorDigitView setCodeText:] : 700 -> 696
~ -[VSTwoFactorDigitView setupDigitViews] : 736 -> 732
~ +[VSMultiAppInstallUtility getPendingConsentBundleIDsFromSelectedAppDescriptions:completionHandler:] : 348 -> 344
~ -[VSTwoFactorEntryViewController_iOS viewDidLoad] : 3204 -> 3196
~ -[VSApplicationController application:evaluateAppJavascriptInContext:] : 2188 -> 2184
~ -[VSApplicationController _applicationControllerAlertForJavascriptAlert:] : 744 -> 740
~ -[VSAppDocumentController _updateViewModel:error:] : 972 -> 964
~ -[VSAppDocumentController _getSupportedButtonTextsforTemplate:andElementKeys:supportedCount:] : 980 -> 976
~ -[VSAppDocumentController userInterfaceStyleDidUpdate] : 568 -> 564
~ ___64-[VSFeaturedIdentityProviderLimitingOperation executionDidBegin]_block_invoke : 680 -> 676
~ -[UIViewController(VSAdditions) _forceViewReload] : 300 -> 296
~ -[VSAMSIdentityProviderResponseDictionaryValueTransformer transformedValue:] : 3692 -> 3688
~ -[VSCredentialEntryAppDocumentController _startObservingViewModel:] : 392 -> 388
~ -[VSCredentialEntryAppDocumentController _stopObservingViewModel:] : 388 -> 384
~ -[VSCredentialEntryAppDocumentController _updateCredentialEntryViewModel:withTemplate:error:] : 3044 -> 3032
~ -[VSLoadAllAppIconsOperation executionDidBegin] : 1152 -> 1148
~ -[VSApplicationControllerResponseHandler _handleJavascriptResponseInternal:requestType:accountAuthentication:completionHandler:] : 1532 -> 1528
~ ___53-[VSIdentityProviderFetchOperation executionDidBegin]_block_invoke_2 : 716 -> 712
~ -[VSViewServiceViewController _determinePreAuthAppIsAuthorized:completion:] : 788 -> 784
~ -[VSViewServiceViewController identityProviderViewController:didAuthenticateAccount:forRequest:] : 596 -> 592
~ ___54-[VSWebAuthenticationViewController _retrieveMessages]_block_invoke : 900 -> 896
~ ___51-[VSWebAuthenticationViewController _sendMessages:]_block_invoke : 720 -> 716
~ -[VSImageElementHelper bestMatchingKeyForSrcset:] : 480 -> 476
~ -[VSImageElementHelper matchingKeyForScale:withSuffix:inKeysSet:] : 344 -> 340
~ +[VSJSSubscription toVSSubscriptions:] : 324 -> 320
~ -[VSWebAuthenticationAppDocumentController didAddMessagesToMessageQueue:] : 1004 -> 1000
~ -[VSIdentityProviderPickerViewController_iOS deselectSelectedProviderAnimated:] : 276 -> 272
~ -[VSIdentityProviderButtonView removeAllButtons] : 268 -> 264
~ -[IKViewElement(VSAdditions) vs_itemElementsOfType:] : 320 -> 316
~ -[VSFooterMessageView initWithSpecifier:] : 1776 -> 1772
~ -[VSCredentialEntryViewModel validateCredentialEntryFields] : 328 -> 324
~ ___85-[VSSetupFlowPreparationOperation _getSTBProviderFromAllProviders:completionHandler:]_block_invoke : 548 -> 544
~ ___71-[VSSetupFlowPreparationOperation _loadProviderAppDescriptionWithFlow:]_block_invoke : 496 -> 492
~ -[VSNonChannelAppDecider decidedNonChannelApps] : 864 -> 852
~ -[VSCredentialEntryViewController_iOS _specifierForTextField:] : 344 -> 340
~ -[VSCredentialEntryViewController_iOS _credentialEntryFieldForSpecifier:] : 400 -> 396
~ -[VSCredentialEntryViewController_iOS setViewModel:] : 1120 -> 1116
~ -[VSCredentialEntryViewController_iOS buildButtonsIfNeeded] : 960 -> 956
~ -[VSCredentialEntryViewController_iOS cancelButtonTapped:] : 308 -> 304
~ -[VSCredentialEntryViewController_iOS viewWillTransitionToSize:withTransitionCoordinator:] : 308 -> 304
~ -[VSAutoAuthenticationViewController_iOS viewDidLoad] : 3084 -> 3080
~ -[VSAppsOperation createAppsResult] : 1100 -> 1096
~ ___75+[UIColor(VSAdditions) vsa_dynamicColorWithLightStyleColor:darkStyleColor:]_block_invoke : 80 -> 76
~ -[VSAppDescription shortenedDisplayName] : 776 -> 764
~ -[VSAppSettingsFacade updateDecidedApps] : 552 -> 548
~ ___34-[VSAppSettingsFacade _updateApps]_block_invoke_2 : 1624 -> 1608
~ -[VSAppSettingsFacade viewModelsForAvailableAppDescriptions:subscribedAppDescriptions:andNonChannelAppDescriptions:] : 980 -> 972
~ -[VSAppSettingsFacade viewModelsForAppDescriptions:bundleByBundleID:vouchersForProvider:restrictionsCenter:privacyFacade:] : 928 -> 924
~ -[VSIdentityProviderRequestManager _identityProviderAlertWithApplicationControllerAlert:] : 524 -> 520
~ -[VSIdentityProviderRequestManager _enqueueUserAccountUpdateOperationIfRequiredForResponse:asDependencyOf:] : 1160 -> 1152
~ -[VSIdentityProviderTableViewDataSource setIdentityProviders:] : 1652 -> 1640
~ -[VSIdentityProviderTableViewDataSource setTvProviderSupportedStorefronts:] : 480 -> 476
~ -[VSIdentityProviderTableViewDataSource preferredIndexPathForIdentityProviderWithName:] : 576 -> 572
~ -[VSIdentityProviderTableViewDataSource _textAlignmentForRowAtIndexPath:] : 104 -> 56
~ -[VSSupportedAppsViewController _displayApps] : 432 -> 428
~ -[VSAMSChannelAppsResponseDictionaryValueTransformer parseAppData:] : 844 -> 840
~ sub_2ab2ed2c8 -> sub_2ac9860e4 : 280 -> 276
```
