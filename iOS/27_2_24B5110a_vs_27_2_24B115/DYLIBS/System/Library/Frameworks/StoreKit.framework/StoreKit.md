## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f4500` | `0x1f996c` | **`+0x546c`** |
| `__DATA.__bss` | `0x26110` | `0x26a90` | **`+0x980`** |
| `__TEXT.__const` | `0x192e4` | `0x197c4` | **`+0x4e0`** |
| `__AUTH_CONST.__const` | `0x17f60` | `0x183b0` | **`+0x450`** |
| `__TEXT.__eh_frame` | `0x12c78` | `0x12ff0` | **`+0x378`** |
| `__TEXT.__unwind_info` | `0xa0e0` | `0xa298` | **`+0x1b8`** |
| `__TEXT.__swift5_fieldmd` | `0x5960` | `0x5a70` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x669a` | `0x678c` | **`+0xf2`** |
| `__AUTH_CONST.__objc_const` | `0x16a20` | `0x16ae8` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x3ba4` | `0x3c54` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x4744` | `0x47ec` | **`+0xa8`** |
| `__DATA.__data` | `0x6888` | `0x6928` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x3c50` | `0x3ce4` | **`+0x94`** |
| `__AUTH.__data` | `0x2830` | `0x28c0` | **`+0x90`** |
| `__TEXT.__swift5_proto` | `0x15f8` | `0x164c` | **`+0x54`** |
| `__TEXT.__swift_as_cont` | `0x11dc` | `0x1224` | **`+0x48`** |
| `__TEXT.__cstring` | `0x8451` | `0x8491` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x7f8` | `0x814` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x7b4` | `0x7cc` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x700` | `0x714` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x1dd0` | `0x1dc0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x19a0` | `0x19a8` | **`+0x8`** |

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 15830
-  Symbols:   7223
-  CStrings:  1363
+  Functions: 15933
+  Symbols:   7243
+  CStrings:  1368
Symbols:
+ ___swift_closure_destructor.149Tm
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.252Tm
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
- ___swift_closure_destructor.165Tm
- ___swift_closure_destructor.205Tm
- ___swift_closure_destructor.209Tm
- ___swift_closure_destructor.477Tm
- ___swift_closure_destructor.64Tm
CStrings:
+ "00:49:59"
+ "InAppReviewResponse"
+ "Oct  8 2026"
+ "ReviewViaSpringBoardRemoteAlert"
+ "Subs4Orgs"
+ "UseStoreKitBag"
+ "UseStoreKitService"
+ "]: Error requesting review: "
- "01:59:39"
- "Oct  4 2026"
- "[In-App Review Prompt] This feature is not supported on beta builds."
```
