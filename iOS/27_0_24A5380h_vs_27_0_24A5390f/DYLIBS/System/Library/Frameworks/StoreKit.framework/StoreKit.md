## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e9e78` | `0x1ed808` | **`+0x3990`** |
| `__TEXT.__eh_frame` | `0x11a38` | `0x127b0` | **`+0xd78`** |
| `__TEXT.__unwind_info` | `0x97e8` | `0x9e20` | **`+0x638`** |
| `__AUTH_CONST.__objc_const` | `0x16d10` | `0x169b8` | **`-0x358`** |
| `__TEXT.__const` | `0x182f4` | `0x185b4` | **`+0x2c0`** |
| `__AUTH_CONST.__const` | `0x17590` | `0x177c8` | **`+0x238`** |
| `__TEXT.__swift5_typeref` | `0x627a` | `0x6452` | **`+0x1d8`** |
| `__TEXT.__swift5_capture` | `0x3a3c` | `0x3b7c` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x18f0` | `0x1800` | **`-0xf0`** |
| `__DATA.__bss` | `0x24930` | `0x24a10` | **`+0xe0`** |
| `__TEXT.__swift_as_cont` | `0x10c0` | `0x11a0` | **`+0xe0`** |
| `__TEXT.__dlopen_cstrs` | `0x498` | `0x3d0` | **`-0xc8`** |
| `__TEXT.__swift_as_entry` | `0x6d8` | `0x7a0` | **`+0xc8`** |
| `__TEXT.__swift_as_ret` | `0x728` | `0x7e0` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x37c0` | `0x3760` | **`-0x60`** |
| `__DATA.__data` | `0x6680` | `0x66e0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3148` | `0x30f8` | **`-0x50`** |
| `__TEXT.__cstring` | `0x84c1` | `0x8471` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0xdb8` | `0xd78` | **`-0x40`** |
| `__AUTH.__data` | `0x27f0` | `0x2820` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x2cb0` | `0x2c80` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0xb80` | `0xbb0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x458c` | `0x45b4` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x5c7c` | `0x5c5c` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x1db0` | `0x1dc0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x5794` | `0x57a4` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3b04` | `0x3b14` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb80` | `0xb78` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1544` | `0x154c` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x30` | **`+0x4`** |

### Other Changes

```diff

-816.0.38.0.0
+816.0.41.0.0

-  Functions: 15437
-  Symbols:   7167
-  CStrings:  1371
+  Functions: 15483
+  Symbols:   7152
+  CStrings:  1362
Symbols:
+ ___swift_closure_destructor.158Tm
+ ___swift_closure_destructor.477Tm
+ ___swift_closure_destructor.77Tm
+ ___swift_closure_destructor.87Tm
+ _symbolic $s8StoreKit17ServiceConnectionP
+ _symbolic ______pScCySS______pGIegnn_ 8StoreKit34OfferCodeRedemptionDisplayProtocolP s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ 8StoreKit0aB34UISceneServiceOfferDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ 8StoreKit40PartnerReferralRedemptionDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ 8StoreKit34ManageSubscriptionsDisplayProtocolP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ 8StoreKit39TransactionRefundRequestDisplayProtocolP s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ 8StoreKit0aB34UISceneServiceOfferDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ 8StoreKit40PartnerReferralRedemptionDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____SSSg______pSgIeghng_Iegngg_ 8StoreKit34OfferCodeRedemptionDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ 8StoreKit34ManageSubscriptionsDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ 8StoreKit39TransactionRefundRequestDisplayProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p______pSgIeghg_Iegng_ So23TransactionCacheServiceP s5ErrorP
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA19OfferDisplayRequestV
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA24TransactionRefundRequestV
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA26ManageSubscriptionsRequestV
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA26OfferCodeRedemptionRequestV
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA32PartnerReferralRedemptionRequestV
- -[SKAccountPageSpecifierProvider _accountPageSpecifierWasTapped:]
- -[SKAccountPageSpecifierProvider _shouldShowActionSheet]
- -[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]
- GCC_except_table16
- _AppleMediaServicesLibrary
- _AppleMediaServicesLibraryCore.frameworkLibrary
- _OBJC_CLASS_$_AMSBoolean
- ___56-[SKAccountPageSpecifierProvider _shouldShowActionSheet]_block_invoke
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_2
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_3
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_4
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_5
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_6
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_7
- ___63-[SKAccountPageSpecifierProvider _showActionSheetForSpecifier:]_block_invoke_8
- ___65-[SKAccountPageSpecifierProvider _accountPageSpecifierWasTapped:]_block_invoke
- ___65-[SKAccountPageSpecifierProvider _accountPageSpecifierWasTapped:]_block_invoke_2
- ___AppleMediaServicesLibraryCore_block_invoke
- ___block_descriptor_32_e30_"AMSPromise"16?0"NSNumber"8l
- ___block_descriptor_48_e8_32s40s_e20_v20?0B8"NSError"12ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e23_v16?0"UIAlertAction"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e32_v24?0"AMSBoolean"8"NSError"16ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e23_v16?0"UIAlertAction"8ls32l8s40l8s48l8
- ___getAMSBagClass_block_invoke
- ___getAMSBiometricsClass_block_invoke
- ___getAMSUIPasswordSettingsViewControllerClass_block_invoke
- ___swift_closure_destructor.184Tm
- ___swift_closure_destructor.18Tm
- ___swift_closure_destructor.76Tm
- ___swift_closure_destructor.97Tm
- ___unnamed_6
- _audit_stringAppleMediaServices
- _getAMSBagClass.softClass
- _getAMSBiometricsClass.softClass
- _getAMSUIPasswordSettingsViewControllerClass.softClass
CStrings:
+ "05:47:57"
+ "Invalid subscription group ID to check introductory offer eligibility"
+ "Jul 11 2026"
+ "StoreKit/IntroOfferEligibilityRequest"
- "%s Failed to encode request: %{public}@"
- "23:17:36"
- "@\"AMSPromise\"16@?0@\"NSNumber\"8"
- "AMSBag"
- "AMSBiometrics"
- "AMSUIPasswordSettingsViewController"
- "Accounts"
- "Jun 27 2026"
- "PASSWORD_SETTINGS"
- "account-page-shows-action-sheet"
- "isPendingUnbundle"
- "softlink:r:path:/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices"
- "v24@?0@\"AMSBoolean\"8@\"NSError\"16"
```
