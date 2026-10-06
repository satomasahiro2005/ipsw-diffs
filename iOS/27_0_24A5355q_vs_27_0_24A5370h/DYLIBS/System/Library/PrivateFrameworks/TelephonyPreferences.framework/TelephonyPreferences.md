## TelephonyPreferences

> `/System/Library/PrivateFrameworks/TelephonyPreferences.framework/TelephonyPreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30d18` | `0x30c4c` | **`-0xcc`** |

### Other Changes

```diff

-400.100.1.0.0
+401.100.1.0.0
Functions:
~ ___76-[PHCallBlockingAndIdentificationSettingsBundleController _updateExtensions]_block_invoke_2 : 572 -> 568
~ -[PHBrandedCallingController featureEnabledForAtLeastOneContext] : 276 -> 272
~ -[PHBrandedCallingController fetchSubscriptionsInUse] : 648 -> 644
~ -[PHBrandedCallingController updateBrandedCallingState] : 516 -> 512
~ -[PHBusinessCallingListController specifiers] : 876 -> 872
~ -[PHBusinessConnectCallingController specifiers] : 792 -> 788
~ -[PHCallBlockingServiceProviderController fetchServiceProviders] : 520 -> 516
~ -[PHLiveLookupSettingsController tableView:moveRowAtIndexPath:toIndexPath:] : 556 -> 552
~ ___51-[PHLiveLookupSettingsController _updateExtensions]_block_invoke : 712 -> 708
~ -[PHLiveLookupSettingsController _isUniqueExtension:] : 440 -> 436
~ -[PHLiveLookupSettingsController createExtensionsGroupSpecifiers] : 1316 -> 1308
~ -[PHCallDirectorySettingsController tableView:moveRowAtIndexPath:toIndexPath:] : 620 -> 616
~ ___54-[PHCallDirectorySettingsController _updateExtensions]_block_invoke_2 : 560 -> 556
~ -[PHCallDirectorySettingsController createExtensionsGroupSpecifiers] : 912 -> 908
~ ___52-[DefaultSpamFilterListController _updateExtensions]_block_invoke : 336 -> 332
~ ___62-[TPSRegistrationTelephonyController performDelegateSelector:]_block_invoke : 420 -> 416
~ -[TPSCloudCallingDeviceListController deviceSwitchSpecifiers] : 564 -> 560
~ -[TPSCloudCallingThumperController subscriptionCapabilities] : 392 -> 388
~ -[TPSBundleController specifiersWithSpecifier:] : 844 -> 836
~ -[TPSSubscriptionListController specifiers] : 748 -> 744
~ ___50-[TPSCarrierBundleController carrierBundleChange:]_block_invoke : 452 -> 448
~ ___51-[TPSCarrierBundleController operatorBundleChange:]_block_invoke : 452 -> 448
~ -[TPSCloudCallingURLController subscriptionCapabilitiesForSubscriptionContextUUID:] : 356 -> 352
~ -[TPSCallForwardingController sendConditionalServicesRequest] : 380 -> 376
~ -[TPSCallForwardingController sendUnconditionalServicesRequest] : 380 -> 376
~ ___62-[TPSSubscriberTelephonyController setSIMPasscodeLockEnabled:]_block_invoke_2 : 432 -> 428
~ ___68-[TPSSubscriberTelephonyController setSIMPasscodeRemainingAttempts:]_block_invoke_2 : 428 -> 424
~ ___49-[TPSSubscriberTelephonyController setSIMStatus:]_block_invoke_2 : 452 -> 448
~ ___74-[TPSSubscriberTelephonyController simLockSaveRequestDidComplete:success:]_block_invoke : 432 -> 428
~ ___68-[TPSSubscriberTelephonyController simPinEntryErrorDidOccur:status:]_block_invoke : 424 -> 420
~ ___68-[TPSSubscriberTelephonyController simPukEntryErrorDidOccur:status:]_block_invoke : 424 -> 420
~ ___75-[TPSSubscriberTelephonyController simPinChangeRequestDidComplete:success:]_block_invoke : 432 -> 428
~ -[TPSRequestController postResponse:] : 548 -> 544
~ ___49-[TPSTelephonyController setActiveSubscriptions:]_block_invoke_2 : 424 -> 420
~ ___43-[TPSTelephonyController setSubscriptions:]_block_invoke_2 : 424 -> 420
~ -[TPSTelephonyController fetchNonHiddenSubscriptions] : 748 -> 744
~ -[TPSTelephonyController fetchSystemCapabilitiesForSubscriptions:] : 380 -> 376
~ +[TPSSubscriptionLabeler localizedLabelsForLabels:languageStringOverrides:] : 376 -> 372
~ +[TPSSubscriptionLabeler localizedBadgeLabelsForUnlocalizedLabels:languageStringOverrides:] : 408 -> 404
~ +[TPSSubscriptionLabeler stringsByClippingStrings:toWidthOfString:] : 688 -> 684
~ +[TPSSubscriptionLabeler stringsByNumericallyDisambiguatingStrings:] : 836 -> 828
~ +[TPSSubscriptionLabeler _dictionary:containsCollationEquivalentKey:] : 288 -> 284
~ +[TPSSubscriptionLabeler _resultWithAllCharacters:string:] : 392 -> 388
~ -[TPSCellularNetworkController setNetworks:] : 388 -> 384
~ -[TPSWiFiCallingController subscriptionCapabilitiesForSubscriptionContextUUID:] : 356 -> 352
~ ___54-[TPSPhonebookTelephonyController setPhoneNumberInfo:]_block_invoke_2 : 452 -> 448
~ sub_2a6d56a6c -> sub_2a87bb9a8 : 1136 -> 1132
~ sub_2a6d573b8 -> sub_2a87bc2f0 : 936 -> 932
~ sub_2a6d578b8 -> sub_2a87bc7ec : 248 -> 252
~ sub_2a6d5814c -> sub_2a87bd084 : 344 -> 340
```
