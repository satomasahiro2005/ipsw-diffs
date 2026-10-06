## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e3184` | `0x1e1be0` | **`-0x15a4`** |
| `__DATA.__bss` | `0x28030` | `0x277b0` | **`-0x880`** |
| `__TEXT.__const` | `0x18434` | `0x18084` | **`-0x3b0`** |
| `__AUTH_CONST.__const` | `0x16b80` | `0x168c0` | **`-0x2c0`** |
| `__TEXT.__eh_frame` | `0x110c8` | `0x10e30` | **`-0x298`** |
| `__AUTH_CONST.__objc_const` | `0x16518` | `0x16600` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0x9678` | `0x95a8` | **`-0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x584c` | `0x5788` | **`-0xc4`** |
| `__TEXT.__swift5_typeref` | `0x5d34` | `0x5cac` | **`-0x88`** |
| `__AUTH.__data` | `0x33b8` | `0x3348` | **`-0x70`** |
| `__AUTH.__objc_data` | `0x23e0` | `0x2450` | **`+0x70`** |
| `__DATA.__data` | `0x70c0` | `0x7050` | **`-0x70`** |
| `__TEXT.__objc_methlist` | `0x5c0c` | `0x5c7c` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x3b44` | `0x3af4` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x45b0` | `0x4564` | **`-0x4c`** |
| `__TEXT.__swift5_proto` | `0x158c` | `0x1540` | **`-0x4c`** |
| `__DATA_CONST.__const` | `0x18a8` | `0x18f0` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x3410` | `0x33d0` | **`-0x40`** |
| `__TEXT.__swift_as_cont` | `0x1168` | `0x112c` | **`-0x3c`** |
| `__TEXT.__cstring` | `0x8471` | `0x84a1` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x17c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3128` | `0x3148` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0xb68` | `0xb80` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x730` | `0x71c` | **`-0x14`** |
| `__DATA_CONST.__got` | `0xb68` | `0xb78` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x688` | `0x67c` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x6d8` | `0x6d0` | **`-0x8`** |

### Other Changes

```diff

-816.0.30.2.1
+816.0.34.0.0

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 15425
-  Symbols:   7104
-  CStrings:  1374
+  Functions: 15375
+  Symbols:   7107
+  CStrings:  1370
Symbols:
+ -[SKPaymentQueue _logPurchaseResult:primaryError:mappedError:inAppPurchaseID:analyticsMetadata:]
+ GCC_except_table16
+ _OBJC_CLASS_$_AMSBoolean
+ _OBJC_CLASS_$_SKPurchaseAnalyticsMetadata
+ _OBJC_METACLASS_$_SKPurchaseAnalyticsMetadata
+ __CLASS_METHODS_SKPurchaseAnalyticsMetadata
+ __DATA_SKPurchaseAnalyticsMetadata
+ __INSTANCE_METHODS_SKPurchaseAnalyticsMetadata
+ __IVARS_SKPurchaseAnalyticsMetadata
+ __METACLASS_DATA_SKPurchaseAnalyticsMetadata
+ __PROPERTIES_SKPurchaseAnalyticsMetadata
+ ___56-[SKAccountPageSpecifierProvider _shouldShowActionSheet]_block_invoke
+ ___65-[SKAccountPageSpecifierProvider _accountPageSpecifierWasTapped:]_block_invoke
+ ___65-[SKAccountPageSpecifierProvider _accountPageSpecifierWasTapped:]_block_invoke_2
+ ___block_descriptor_32_e30_"AMSPromise"16?0"NSNumber"8l
+ ___block_descriptor_48_e8_32s40s_e32_v24?0"AMSBoolean"8"NSError"16ls32l8s40l8
+ ___swift_closure_destructor.159Tm
+ ___swift_closure_destructor.60Tm
+ ___swift_memcpy73_8
+ _objc_retain_x6
+ _swift_release_x13
+ _symbolic _____ 8StoreKit22SKPurchaseEventContextV
+ _symbolic _____ So13SKStoreKitAPIV
+ _symbolic _____ So26SKAnalyticsEnvironmentTypeV
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _type_layout_string 8StoreKit22SKPurchaseEventContextV
- -[SKPaymentQueue _logPurchaseResult:primaryError:mappedError:inAppPurchaseID:]
- ___swift_closure_destructor.13Tm
- ___swift_closure_destructor.149Tm
- _associated conformance 8StoreKit0aB11FeatureFlagOSHAASQ
- _associated conformance 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLOSHAASQ
- _associated conformance 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLOs0G3KeyAAs23CustomStringConvertible
- _associated conformance 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLOs0G3KeyAAs28CustomDebugStringConvertible
- _associated conformance 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLOSHAASQ
- _associated conformance 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLOs0F3KeyAAs28CustomDebugStringConvertible
- _objc_retain_x5
- _symbolic _____ 8StoreKit0aB11FeatureFlagO
- _symbolic _____ 8StoreKit19InAppReviewResponseV
- _symbolic _____ 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLO
- _symbolic _____ 8StoreKit27DisplaySpringboardUIRequestV
- _symbolic _____ 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLO
- _symbolic _____y_____G 8StoreKit11ServiceTaskV AA18InAppReviewRequestV
- _symbolic _____y_____G 8StoreKit11ServiceTaskV AA27DisplaySpringboardUIRequestV
- _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLO
- _type_layout_string 8StoreKit19InAppReviewResponseV
CStrings:
+ "10:00:23"
+ "@\"AMSPromise\"16@?0@\"NSNumber\"8"
+ "Jun 13 2026"
+ "StoreKit_Internal.SKPurchaseAnalyticsMetadata"
+ "[In-App Review Prompt] This feature is not supported on beta builds."
+ "v24@?0@\"AMSBoolean\"8@\"NSError\"16"
- "21:19:31"
- "H"
- "InAppReviewResponse"
- "May 31 2026"
- "ReviewViaSpringBoardRemoteAlert"
- "Subs4Orgs"
- "UseOctane2"
- "UseStoreKitBag"
- "UseStoreKitService"
- "]: Error requesting review: "
```
