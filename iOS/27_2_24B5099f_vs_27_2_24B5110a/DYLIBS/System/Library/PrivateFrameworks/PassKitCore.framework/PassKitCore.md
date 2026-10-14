## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91ef24` | `0x91e56c` | **`-0x9b8`** |
| `__AUTH_CONST.__cfstring` | `0x7a620` | `0x7a540` | **`-0xe0`** |
| `__DATA_CONST.__const` | `0x238c8` | `0x23898` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x72a98` | `0x72a68` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x25420` | `0x25408` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1fee8` | `0x1fed0` | **`-0x18`** |
| `__TEXT.__cstring` | `0x741ce` | `0x741b8` | **`-0x16`** |
| `__AUTH_CONST.__objc_const` | `0xd07b0` | `0xd07c0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1358` | `0x1348` | **`-0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1f50` | `0x1f58` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x734c` | `0x7348` | **`-0x4`** |

### Other Changes

```diff

-1696.2.8.1.0
+1696.2.9.0.0

-  Functions: 55942
-  Symbols:   79224
-  CStrings:  21824
+  Functions: 55937
+  Symbols:   79209
+  CStrings:  21817
Symbols:
+ +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:]
+ +[PKPaymentAuthorizationErrorStateParam paramWithError:requiresExtendedDisplayDuration:]
+ -[PKPaymentAuthorizationErrorStateParam requiresExtendedDisplayDuration]
+ -[PKPaymentAuthorizationErrorStateParam setRequiresExtendedDisplayDuration:]
+ -[PKPaymentProvisioningController allowsUserGeneratedPass]
+ -[PKPaymentProvisioningController includePrecursorPasses]
+ -[PKPaymentProvisioningController setAllowsUserGeneratedPass:]
+ -[PKPaymentProvisioningController setIncludePrecursorPasses:]
+ _OBJC_IVAR_$_PKPaymentAuthorizationErrorStateParam._requiresExtendedDisplayDuration
+ _OBJC_IVAR_$_PKPaymentProvisioningController._allowsUserGeneratedPass
+ _OBJC_IVAR_$_PKPaymentProvisioningController._includePrecursorPasses
+ _PKRemoteNetworkPaymentHostAllowGuestCodeScan
+ _PKRemoteNetworkPaymentHostAllowGuestCodeScanKey
+ _PKRemoteNetworkPaymentHostAllowPersonaCodeScan
+ _PKRemoteNetworkPaymentHostAllowPersonaCodeScanKey
+ _PKRemoteNetworkPaymentHostAllowPersonaDisabledPersonalContentCodeScan
+ _PKRemoteNetworkPaymentHostAllowPersonaDisabledPersonalContentCodeScanKey
- +[PKAnalyticsReporter(Attribution) isNewToWalletUser]
- +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:]
- -[PKPaymentProvisioningController allowUserGeneratedPassInUnsupportedRegion]
- -[PKPaymentProvisioningController setAllowUserGeneratedPassInUnsupportedRegion:]
- -[PKProvisioningAnalyticsSession reportNCCCheck]
- -[PKProvisioningAnalyticsSessionCampaignAttributionSubjectHandle reportNCCCheckWithState:]
- -[PKProvisioningAnalyticsState campaignAttributionNewToProductUser]
- -[PKProvisioningAnalyticsState campaignAttributionNewToWalletUser]
- -[PKProvisioningAnalyticsState campaignAttributionReferralSource]
- -[PKProvisioningAnalyticsState setCampaignAttributionNewToProductUser:]
- -[PKProvisioningAnalyticsState setCampaignAttributionNewToWalletUser:]
- _OBJC_IVAR_$_PKPaymentProvisioningController._allowUserGeneratedPassInUnsupportedRegion
- _OBJC_IVAR_$_PKProvisioningAnalyticsSession._didReportNCCCheck
- _OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToProductUser
- _OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToWalletUser
- _PKAnalyticsReportNewToCreditUserKey
- _PKAnalyticsReportNewToDebitUserKey
- _PKAnalyticsReportNewToTransitUserKey
- _PKAnalyticsReportNewToWalletUserKey
- _PKCurrentSecureElementPasses
- _PKISO23220_1_PhotoID_FamilyNameUnicode
- _PKISO23220_1_PhotoID_GivenNameUnicode
- _PKISO23220_1_PhotoID_IssuingAuthorityUnicode
- _PKPendingCampaignAttributionCampaignIdentifierKey
- _PKPendingCampaignAttributionForPassUniqueIdentifier
- _PKPendingCampaignAttributionNewToProductUserKey
- _PKPendingCampaignAttributionNewToWalletUserKey
- _PKPendingCampaignAttributionProductTypeKey
- _PKPendingCampaignAttributionReferralSourceKey
- _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
- _PKSetLocalSecureElementPassesProvider
- _PKSetPendingCampaignAttributionForPassUniqueIdentifier
CStrings:
+ "PKRemoteNetworkPaymentHostAllowGuestCodeScan"
+ "PKRemoteNetworkPaymentHostAllowPersonaCodeScan"
+ "PKRemoteNetworkPaymentHostAllowPersonaDisabledPersonalContentCodeScan"
+ "requiresExtendedDisplayDuration: '%@'; "
- "PKPendingCampaignAttributionKey"
- "appleAccount"
- "campaignAttributionNewToProductUser"
- "campaignAttributionNewToWalletUser"
- "cardReadyToUse"
- "nccCheck"
- "newToCreditUser"
- "newToDebitUser"
- "newToProductUser"
- "newToTransitUser"
- "newToWalletUser"
```
