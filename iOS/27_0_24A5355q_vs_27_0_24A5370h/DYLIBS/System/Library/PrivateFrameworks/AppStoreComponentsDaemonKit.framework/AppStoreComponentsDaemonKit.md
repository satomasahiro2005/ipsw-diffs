## AppStoreComponentsDaemonKit

> `/System/Library/PrivateFrameworks/AppStoreComponentsDaemonKit.framework/AppStoreComponentsDaemonKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x118a3c` | `0x119928` | **`+0xeec`** |
| `__AUTH.__data` | `0x478` | `0x5d8` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x831c` | `0x81dc` | **`-0x140`** |
| `__DATA_DIRTY.__data` | `0x2360` | `0x2260` | **`-0x100`** |
| `__AUTH_CONST.__objc_const` | `0xa848` | `0xa928` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x62a8` | `0x6238` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x1b4c` | `0x1b98` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0x3880` | `0x38c0` | **`+0x40`** |
| `__DATA.__data` | `0x1b18` | `0x1b48` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3aa8` | `0x3a78` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x1aec` | `0x1ac4` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x176c` | `0x1794` | **`+0x28`** |
| `__TEXT.__cstring` | `0x717c` | `0x719c` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x5a0` | `0x584` | **`-0x1c`** |
| `__DATA.__common` | `0x68` | `0x80` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x3595` | `0x35a7` | **`+0x12`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f90` | `0x1fa0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1e98` | `0x1e90` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x7f0` | `0x7f8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x4a70` | `0x4a78` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x200` | `0x1f8` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2a4` | `0x29c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x3dc` | `0x3e0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x23c` | `0x240` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-27.0.33.0.0
+27.0.38.0.0

-  Functions: 4646
-  Symbols:   4035
-  CStrings:  1064
+  Functions: 4652
+  Symbols:   4041
+  CStrings:  1068
Symbols:
+ -[ASCIAPOffer initWithID:titles:subtitles:flags:ageRating:metrics:productIdentifier:productName:appName:appAdamId:appBundleId:subscriptionFamilyId:minimumShortVersionSupportingInAppPurchaseFlow:additionalBuyParams:streamlinedOffer:]
+ -[ASCIAPOffer subscriptionFamilyId]
+ _ASCOfferTitleVariantPurchased
+ _OBJC_IVAR_$_ASCIAPOffer._subscriptionFamilyId
+ __DATA__TtC27AppStoreComponentsDaemonKit24ASDInAppPurchaseDatabase
+ __DATA__TtC27AppStoreComponentsDaemonKit31ASDInAppPurchaseStateController
+ __IVARS__TtC27AppStoreComponentsDaemonKit31ASDInAppPurchaseStateController
+ __METACLASS_DATA__TtC27AppStoreComponentsDaemonKit24ASDInAppPurchaseDatabase
+ __METACLASS_DATA__TtC27AppStoreComponentsDaemonKit31ASDInAppPurchaseStateController
+ _get_type_metadata 15Synchronization5MutexVy27AppStoreComponentsDaemonKit05ASDInC23PurchaseStateControllerC0J033_88CAC76BBD8C2F405DC135248702BDD0LLVG noncopyable
+ _symbolic $s27AppStoreComponentsDaemonKit02InA23PurchaseStateControllerP
+ _symbolic Ieg_
+ _symbolic SDySo8NSNumberCSo10ASDIAPInfoCG
+ _symbolic So8NSNumberC_So10ASDIAPInfoCt
+ _symbolic _____ 27AppStoreComponentsDaemonKit05ASDInA16PurchaseDatabaseC
+ _symbolic _____ 27AppStoreComponentsDaemonKit05ASDInA23PurchaseStateControllerC
+ _symbolic _____ 27AppStoreComponentsDaemonKit05ASDInA23PurchaseStateControllerC0H033_88CAC76BBD8C2F405DC135248702BDD0LLV
+ _symbolic _____SgXw 27AppStoreComponentsDaemonKit05ASDInA23PurchaseStateControllerC
+ _symbolic _____SgXwz_Xx 27AppStoreComponentsDaemonKit05ASDInA23PurchaseStateControllerC
+ _symbolic ______p 27AppStoreComponentsDaemonKit02InA23PurchaseStateControllerP
+ _symbolic _____ySo8NSNumberCSo10ASDIAPInfoCG s18_DictionaryStorageC
+ _symbolic _____ySo8NSNumberC_So10ASDIAPInfoCtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 27AppStoreComponentsDaemonKit05ASDInC23PurchaseStateControllerC0J033_88CAC76BBD8C2F405DC135248702BDD0LLV
+ _symbolic _____yytG 9JetEngine10AsyncEventC
+ _symbolic _____yytG 9JetEngine17EventSubscriptionV
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
+ _type_layout_string 27AppStoreComponentsDaemonKit05ASDInA23PurchaseStateControllerC0H033_88CAC76BBD8C2F405DC135248702BDD0LLV
- -[ASCIAPOffer initWithID:titles:subtitles:flags:ageRating:metrics:productIdentifier:productName:appName:appAdamId:appBundleId:minimumShortVersionSupportingInAppPurchaseFlow:additionalBuyParams:streamlinedOffer:]
- __DATA__TtC27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManager
- __IVARS__TtC27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManager
- __METACLASS_DATA__TtC27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManager
- _swift_bridgeObjectRelease_n
- _symbolic $s27AppStoreComponentsDaemonKit34ContingentOfferSubscriptionManagerP
- _symbolic Sccyyt______pG s5ErrorP
- _symbolic ShySo8NSNumberCGIegg_
- _symbolic ShySo8NSNumberCGSg
- _symbolic ShySo8NSNumberCGSgIeAgHr_
- _symbolic _____ 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC
- _symbolic _____ 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC5State33_D9E03E4480FEA50667E941DD5B832D35LLV
- _symbolic _____ 8AppState6AdamIDV
- _symbolic _____SgXw 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC
- _symbolic _____SgXwz_Xx 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC
- _symbolic _____XDXMT 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC
- _symbolic ______p 27AppStoreComponentsDaemonKit34ContingentOfferSubscriptionManagerP
- _symbolic _____yShySo8NSNumberCGG 9JetEngine10AsyncEventC
- _symbolic _____yShySo8NSNumberCGG 9JetEngine17EventSubscriptionV
- _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC5State33_D9E03E4480FEA50667E941DD5B832D35LLV
- _symbolic _____y__________G s13ManagedBufferCsRi__rlE 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC5State33_D9E03E4480FEA50667E941DD5B832D35LLV So16os_unfair_lock_sV
- _type_layout_string 27AppStoreComponentsDaemonKit39ASDContingentPricingSubscriptionManagerC5State33_D9E03E4480FEA50667E941DD5B832D35LLV
CStrings:
+ " as an active recurring subscription"
+ " reported no available apps for requested ids "
+ "ASCOfferIsInAppPurchase"
+ "Failed to refresh IAP data, reason: "
+ "Finished refreshing IAP data"
+ "No distributor vended any of the requested apps."
+ "OfferButton.Title.Subscribed"
+ "Received kASDIAPInfoDatabaseUpdatedNotification"
+ "Refreshing IAP data"
+ "Subscription without a family ID encountered"
+ "Updated IAP state"
+ "Updating IAP state"
+ "Updating offers for IAP state change"
+ "description,latestVersionInfo,messagesScreenshots,screenshotsByType"
+ "description,messagesScreenshots,screenshotsByType,shortName"
+ "rdar://158957691 workaround – temporarily marking "
+ "subscriptionFamilyId"
- "Adding temporary active recurring IAP subscription: "
- "Contingent Pricing Purchases"
- "Could not update Contingent Offer subscriptions state, reason: "
- "Error fetching active recurring IAP subscriptions from asd: "
- "Failed to update Contingent Offer subscription state during bootstrap, reason: "
- "Refreshing active recurring IAP subscriptions"
- "Successfully fetched active recurring IAP subscriptions using asd: "
- "Updated Contingent Offer subscriptions state to "
- "Updating Contingent Offer subscriptions state"
- "Updating offers for contingent purchases change"
- "description,latestVersionInfo,screenshotsByType"
- "description,screenshotsByType,shortName"
- "kASDIAPInfoDatabaseUpdatedNotification received"
```
