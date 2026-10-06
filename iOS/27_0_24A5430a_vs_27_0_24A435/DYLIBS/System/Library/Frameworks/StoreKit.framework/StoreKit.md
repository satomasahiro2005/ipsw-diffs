## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f2d48` | `0x1f761c` | **`+0x48d4`** |
| `__DATA.__bss` | `0x25e90` | `0x26810` | **`+0x980`** |
| `__TEXT.__const` | `0x19194` | `0x19674` | **`+0x4e0`** |
| `__AUTH_CONST.__const` | `0x17ee0` | `0x18330` | **`+0x450`** |
| `__TEXT.__eh_frame` | `0x128d8` | `0x12cb0` | **`+0x3d8`** |
| `__TEXT.__unwind_info` | `0x9fc8` | `0xa158` | **`+0x190`** |
| `__TEXT.__swift5_fieldmd` | `0x5904` | `0x5a14` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x665a` | `0x674c` | **`+0xf2`** |
| `__AUTH_CONST.__objc_const` | `0x16a20` | `0x16ae8` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x3b84` | `0x3c34` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x4700` | `0x47a8` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x3c4c` | `0x3ce0` | **`+0x94`** |
| `__AUTH.__data` | `0x27a0` | `0x2830` | **`+0x90`** |
| `__DATA.__data` | `0x6860` | `0x68e0` | **`+0x80`** |
| `__TEXT.__swift5_proto` | `0x15e4` | `0x1638` | **`+0x54`** |
| `__TEXT.__swift_as_cont` | `0x1194` | `0x11dc` | **`+0x48`** |
| `__TEXT.__cstring` | `0x8451` | `0x8491` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x7dc` | `0x7f8` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x79c` | `0x7b4` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x6f8` | `0x70c` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x1dc0` | `0x1db0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x19a0` | `0x19a8` | **`+0x8`** |

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 15695
-  Symbols:   7210
-  CStrings:  1363
+  Functions: 15859
+  Symbols:   7241
+  CStrings:  1368
Symbols:
+ _OUTLINED_FUNCTION_594
+ _OUTLINED_FUNCTION_595
+ _OUTLINED_FUNCTION_596
+ _OUTLINED_FUNCTION_597
+ _OUTLINED_FUNCTION_598
+ _OUTLINED_FUNCTION_599
+ _OUTLINED_FUNCTION_600
+ _OUTLINED_FUNCTION_601
+ _OUTLINED_FUNCTION_602
+ _OUTLINED_FUNCTION_603
+ ___swift_closure_destructor.148Tm
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.205Tm
+ ___swift_closure_destructor.43Tm
+ ___swift_closure_destructor.505Tm
+ _associated conformance 8StoreKit0aB11FeatureFlagOSHAASQ
+ _associated conformance 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLOSHAASQ
+ _associated conformance 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLOSHAASQ
+ _associated conformance 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 8StoreKit0aB11FeatureFlagO
+ _symbolic _____ 8StoreKit19InAppReviewResponseV
+ _symbolic _____ 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLO
+ _symbolic _____ 8StoreKit27DisplaySpringboardUIRequestV
+ _symbolic _____ 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLO
+ _symbolic ______pScCy___________pGIegnn_ So13ReviewServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So13ReviewServiceP 10Foundation4DataV s5ErrorP
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA18InAppReviewRequestV
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA27DisplaySpringboardUIRequestV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit19InAppReviewResponseV10CodingKeys33_D077A3D4D78AADD1849BB180859159C1LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit27DisplaySpringboardUIRequestV10CodingKeys33_E166EFEFD72548DC040978D3622A82A0LLO
+ _type_layout_string 8StoreKit19InAppReviewResponseV
- ___swift_closure_destructor.158Tm
- ___swift_closure_destructor.164Tm
- ___swift_closure_destructor.208Tm
- ___swift_closure_destructor.477Tm
- ___swift_closure_destructor.63Tm
CStrings:
+ "22:06:54"
+ "Aug  9 2026"
+ "InAppReviewResponse"
+ "ReviewViaSpringBoardRemoteAlert"
+ "Subs4Orgs"
+ "UseStoreKitBag"
+ "UseStoreKitService"
+ "]: Error requesting review: "
- "06:14:03"
- "Aug 10 2026"
- "[In-App Review Prompt] This feature is not supported on beta builds."
```
