## StoreKitUIService

> `/Applications/StoreKitUIService.app/StoreKitUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x9ebd` | `0x97b0` | **`-0x70d`** |
| `__TEXT.__text` | `0x38020` | `0x38514` | **`+0x4f4`** |
| `__TEXT.__objc_methtype` | `0x344d` | `0x2f6d` | **`-0x4e0`** |
| `__TEXT.__objc_methlist` | `0x3d2c` | `0x3b6c` | **`-0x1c0`** |
| `__TEXT.__eh_frame` | `0xaa8` | `0xc20` | **`+0x178`** |
| `__DATA.__objc_const` | `0xa638` | `0xa500` | **`-0x138`** |
| `__DATA.__objc_selrefs` | `0x26f0` | `0x25c8` | **`-0x128`** |
| `__TEXT.__const` | `0x2044` | `0x20f4` | **`+0xb0`** |
| `__DATA.__bss` | `0x3090` | `0x3110` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x23b0` | `0x2348` | **`-0x68`** |
| `__TEXT.__unwind_info` | `0x13b8` | `0x1400` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x6700` | `0x66c0` | **`-0x40`** |
| `__TEXT.__objc_classname` | `0x1051` | `0x1021` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x826` | `0x850` | **`+0x2a`** |
| `__DATA.__data` | `0x2c20` | `0x2bf8` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0x844` | `0x86c` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x654` | `0x62c` | **`-0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x2760` | `0x2740` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1cd1` | `0x1cb1` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x90` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x288` | `0x278` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x75c` | `0x76c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x536` | `0x546` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xb8` | `0xb0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x18c` | `0x190` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x90` | `0x94` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-816.0.38.0.0
+816.0.41.0.0

-  Functions: 1846
-  Symbols:   681
-  CStrings:  2481
+  Functions: 1860
+  Symbols:   682
+  CStrings:  2411
Symbols:
+ _swift_cvw_instantiateLayoutString
+ _swift_deletedAsyncMethodErrorTu
- _swift_retain_x24
CStrings:
- "ASDOctaneAdNetworkProtocol"
- "ASDOctaneServiceProtocol"
- "addPostbacksFromDictionaries:forBundleID:completion:"
- "buyProductWithConfiguration:bundleID:completion:"
- "buyProductWithID:bundleID:completion:"
- "changeAutoRenewStatus:transactionID:bundleID:completion:"
- "clearOverridesForBundleID:completion:"
- "com.apple.storekit.configuration.xpc"
- "completeAskToBuyRequestWithResponse:transactionID:bundleID:completion:"
- "configurationDataForBundleID:completion:"
- "configureSourceForTestPostbackDictionaries:forBundleID:completion:"
- "deleteAllTransactionsForBundleID:completion:"
- "developerPostbackURLForBundleID:completion:"
- "expireSubscriptionWithProductID:bundleID:completion:"
- "forceRenewalOfSubscriptionWithProductID:bundleID:completion:"
- "getActivePortWithCompletion:"
- "getIntegerValueForIdentifier:forBundleID:completion:"
- "getStorefrontForBundleID:completion:"
- "getStringValueForIdentifier:forBundleID:completion:"
- "getTransactionDataForBundleID:completion:"
- "performAction:transactionID:bundleID:completion:"
- "refreshQueueForBundleId:completion:"
- "registerForEventOfType:forBundleID:withFilterData:completion:"
- "removeConfigurationForBundleID:completion:"
- "retrieveTestPostbacksForBundleID:completion:"
- "revokeEntitlementsForProductIdentifiers:forBundleId:completion:"
- "saveConfigurationAssetData:fileName:forBundleID:completion:"
- "saveConfigurationData:forBundleID:completion:"
- "sendPurchaseIntentForProductIdentifier:bundleID:completion:"
- "sendTestPingbackForBundleID:completion:"
- "setIntegerValue:forIdentifier:forBundleID:completion:"
- "setStoreKitError:forCategory:bundleID:withReply:"
- "setStorefront:forBundleID:completion:"
- "setStringValue:forIdentifier:forBundleID:completion:"
- "startObservingTransactionsForBundleID:completion:"
- "storeKitErrorForCategory:bundleID:withReply:"
- "synchronousRemoteObjectProxyWithErrorHandler:"
- "testingAppsWithCompletion:"
- "unregisterForEventWithIdentifier:forBundleID:"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSArray\">24"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSData\"@\"NSError\">24"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSDictionary\">24"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSError\"@\"NSData\">24"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSError\"@\"NSString\">24"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSURL\">24"
- "v32@0:8@\"NSUUID\"16@\"NSString\"24"
- "v40@0:8@\"NSArray\"16@\"NSString\"24@?<v@?@\"NSArray\"@\"NSError\">32"
- "v40@0:8@\"NSArray\"16@\"NSString\"24@?<v@?@\"NSError\">32"
- "v40@0:8@\"NSData\"16@\"NSString\"24@?<v@?@\"NSError\"@\"NSString\">32"
- "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"NSError\">32"
- "v40@0:8Q16@\"NSString\"24@?<v@?@\"NSError\"@\"NSString\">32"
- "v40@0:8Q16@\"NSString\"24@?<v@?@\"NSError\"q>32"
- "v40@0:8Q16@24@?32"
- "v40@0:8q16@\"NSString\"24@?<v@?q>32"
- "v40@0:8q16@24@?32"
- "v44@0:8B16Q20@\"NSString\"28@?<v@?@\"NSError\">36"
- "v44@0:8B16Q20@28@?36"
- "v48@0:8@\"NSData\"16@\"NSString\"24@\"NSString\"32@?<v@?@\"NSError\">40"
- "v48@0:8@\"NSString\"16Q24@\"NSString\"32@?<v@?@\"NSError\">40"
- "v48@0:8@16Q24@32@?40"
- "v48@0:8q16@\"NSString\"24@\"NSData\"32@?<v@?@\"NSUUID\">40"
- "v48@0:8q16@24@32@?40"
- "v48@0:8q16Q24@\"NSString\"32@?<v@?@\"NSError\">40"
- "v48@0:8q16Q24@\"NSString\"32@?<v@?@\"NSError\"B>40"
- "v48@0:8q16Q24@32@?40"
- "v48@0:8q16q24@\"NSString\"32@?<v@?>40"
- "v48@0:8q16q24@32@?40"
- "v56@0:8@\"NSDictionary\"16@\"NSString\"24@\"NSString\"32q40@?<v@?@\"NSError\">48"
- "v56@0:8@16@24@32q40@?48"
- "validateSKAdNetworkImpression:withPublicKey:forBundleID:source:completion:"
```
