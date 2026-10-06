## ASOctaneSupport

> `/System/Library/PrivateFrameworks/ASOctaneSupport.framework/ASOctaneSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e24` | `0xb20` | **`-0x2304`** |
| `__TEXT.__objc_methlist` | `0x46c` | `0x1dc` | **`-0x290`** |
| `__TEXT.__gcc_except_tab` | `0x2a4` | `0x74` | **`-0x230`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f8` | `0x140` | **`-0x1b8`** |
| `__TEXT.__unwind_info` | `0x270` | `0xd0` | **`-0x1a0`** |
| `__DATA_CONST.__const` | `0x1d8` | `0xe8` | **`-0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x2b8` | `0x1e0` | **`-0xd8`** |
| `__TEXT.__cstring` | `0x138` | `0xd8` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x60` | `0x20` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x48` | `0x20` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0xa0` | `0x80` | **`-0x20`** |
| `__TEXT.__const` | `0x18` | `0x10` | **`-0x8`** |

### Other Changes

```diff

-816.0.38.0.0
+816.0.41.0.0

-  Functions: 78
-  Symbols:   189
-  CStrings:  12
+  Functions: 22
+  Symbols:   96
+  CStrings:  8
Symbols:
+ GCC_except_table10
+ GCC_except_table12
+ GCC_except_table14
+ GCC_except_table16
- -[ASOctaneServer activePort]
- -[ASOctaneServer appRemovedWithBundleID:]
- -[ASOctaneServer buyProductWithConfiguration:withReply:]
- -[ASOctaneServer buyProductWithID:bundleID:]
- -[ASOctaneServer cancelTransactionWithIdentifier:forBundleID:]
- -[ASOctaneServer changeAutoRenewStatus:transactionID:bundleID:]
- -[ASOctaneServer clearOverridesForBundleID:]
- -[ASOctaneServer completeAskToBuyRequestWithResponse:transactionID:forBundleID:]
- -[ASOctaneServer completePriceConsentRequestWithResponse:transactionIdentifier:forBundleID:]
- -[ASOctaneServer deleteTransactionWithIdentifier:forBundleID:]
- -[ASOctaneServer expireOrRenewSubscriptionWithIdentifier:expire:forBundleID:]
- -[ASOctaneServer getIntegerValueForIdentifier:forBundleID:]
- -[ASOctaneServer getIntegerValueForIdentifier:forBundleID:completion:]
- -[ASOctaneServer getStorefrontForBundleID:]
- -[ASOctaneServer getTransactionDataForBundleID:]
- -[ASOctaneServer messageForBundleID:]
- -[ASOctaneServer messageOfTypeForBundleID:messageReason:]
- -[ASOctaneServer refundTransactionWithIdentifier:forBundleID:]
- -[ASOctaneServer registerForEventOfType:withFilterData:]
- -[ASOctaneServer resolveIssueForTransactionWithIdentifier:forBundleID:]
- -[ASOctaneServer setIntegerValue:forIdentifier:forBundleID:]
- -[ASOctaneServer setStoreKitError:forCategory:bundleID:]
- -[ASOctaneServer setStorefront:forBundleID:]
- -[ASOctaneServer setStringValue:forIdentifier:forBundleID:]
- -[ASOctaneServer startPriceIncreaseForTransactionID:bundleID:needsConsent:]
- -[ASOctaneServer storeKitErrorForCategory:bundleID:]
- -[ASOctaneServer unregisterForEventWithIdentifier:]
- -[ASOctaneServer useConfigurationDirectory:forBundleID:]
- GCC_except_table13
- GCC_except_table15
- GCC_except_table17
- GCC_except_table19
- GCC_except_table21
- GCC_except_table23
- GCC_except_table25
- GCC_except_table27
- GCC_except_table29
- GCC_except_table34
- GCC_except_table36
- GCC_except_table38
- GCC_except_table42
- GCC_except_table45
- GCC_except_table47
- GCC_except_table49
- GCC_except_table51
- GCC_except_table53
- GCC_except_table55
- GCC_except_table57
- GCC_except_table61
- GCC_except_table66
- GCC_except_table68
- GCC_except_table70
- GCC_except_table72
- GCC_except_table9
- _OBJC_CLASS_$_NSDictionary
- _OBJC_CLASS_$_NSNumber
- _OBJC_CLASS_$_NSSet
- _OBJC_CLASS_$_NSString
- _OBJC_CLASS_$_NSURL
- ___28-[ASOctaneServer activePort]_block_invoke
- ___37-[ASOctaneServer messageForBundleID:]_block_invoke
- ___41-[ASOctaneServer appRemovedWithBundleID:]_block_invoke
- ___43-[ASOctaneServer getStorefrontForBundleID:]_block_invoke
- ___44-[ASOctaneServer buyProductWithID:bundleID:]_block_invoke
- ___44-[ASOctaneServer clearOverridesForBundleID:]_block_invoke
- ___44-[ASOctaneServer setStorefront:forBundleID:]_block_invoke
- ___48-[ASOctaneServer getTransactionDataForBundleID:]_block_invoke
- ___52-[ASOctaneServer storeKitErrorForCategory:bundleID:]_block_invoke
- ___56-[ASOctaneServer buyProductWithConfiguration:withReply:]_block_invoke
- ___56-[ASOctaneServer registerForEventOfType:withFilterData:]_block_invoke
- ___56-[ASOctaneServer setStoreKitError:forCategory:bundleID:]_block_invoke
- ___56-[ASOctaneServer useConfigurationDirectory:forBundleID:]_block_invoke
- ___57-[ASOctaneServer messageOfTypeForBundleID:messageReason:]_block_invoke
- ___59-[ASOctaneServer getIntegerValueForIdentifier:forBundleID:]_block_invoke
- ___59-[ASOctaneServer setStringValue:forIdentifier:forBundleID:]_block_invoke
- ___60-[ASOctaneServer setIntegerValue:forIdentifier:forBundleID:]_block_invoke
- ___62-[ASOctaneServer cancelTransactionWithIdentifier:forBundleID:]_block_invoke
- ___62-[ASOctaneServer deleteTransactionWithIdentifier:forBundleID:]_block_invoke
- ___62-[ASOctaneServer refundTransactionWithIdentifier:forBundleID:]_block_invoke
- ___63-[ASOctaneServer changeAutoRenewStatus:transactionID:bundleID:]_block_invoke
- ___70-[ASOctaneServer getIntegerValueForIdentifier:forBundleID:completion:]_block_invoke
- ___70-[ASOctaneServer getIntegerValueForIdentifier:forBundleID:completion:]_block_invoke_2
- ___71-[ASOctaneServer resolveIssueForTransactionWithIdentifier:forBundleID:]_block_invoke
- ___75-[ASOctaneServer startPriceIncreaseForTransactionID:bundleID:needsConsent:]_block_invoke
- ___77-[ASOctaneServer expireOrRenewSubscriptionWithIdentifier:expire:forBundleID:]_block_invoke
- ___80-[ASOctaneServer completeAskToBuyRequestWithResponse:transactionID:forBundleID:]_block_invoke
- ___92-[ASOctaneServer completePriceConsentRequestWithResponse:transactionIdentifier:forBundleID:]_block_invoke
- ___block_descriptor_40_e8_32bs_e8_v16?0q8ls32l8
- ___block_descriptor_40_e8_32r_e16_v16?0"NSData"8lr32l8
- ___block_descriptor_40_e8_32r_e16_v16?0"NSUUID"8lr32l8
- ___block_descriptor_40_e8_32r_e22_v16?0"NSDictionary"8lr32l8
- ___block_descriptor_40_e8_32r_e8_v16?0q8lr32l8
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- _objc_opt_class
- _objc_release_x22
- _objc_retain_x22
- _objc_retain_x4
CStrings:
- "Error setting configuration file %@ for %@: %@"
- "v16@?0@\"NSDictionary\"8"
- "v16@?0@\"NSUUID\"8"
- "v16@?0q8"
```
