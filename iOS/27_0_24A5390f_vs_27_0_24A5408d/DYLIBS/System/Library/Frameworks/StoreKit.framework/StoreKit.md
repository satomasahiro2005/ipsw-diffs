## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed808` | `0x1f2d48` | **`+0x5540`** |
| `__DATA.__bss` | `0x24a10` | `0x25e90` | **`+0x1480`** |
| `__TEXT.__const` | `0x185b4` | `0x19194` | **`+0xbe0`** |
| `__AUTH_CONST.__const` | `0x177c8` | `0x17ee0` | **`+0x718`** |
| `__TEXT.__swift5_typeref` | `0x6452` | `0x665a` | **`+0x208`** |
| `__TEXT.__unwind_info` | `0x9e20` | `0x9fc8` | **`+0x1a8`** |
| `__DATA.__data` | `0x66e0` | `0x6860` | **`+0x180`** |
| `__TEXT.__swift5_fieldmd` | `0x57a4` | `0x5904` | **`+0x160`** |
| `__TEXT.__constg_swiftt` | `0x45b4` | `0x4700` | **`+0x14c`** |
| `__TEXT.__eh_frame` | `0x127b0` | `0x128d8` | **`+0x128`** |
| `__TEXT.__swift5_capture` | `0x3b7c` | `0x3c4c` | **`+0xd0`** |
| `__TEXT.__swift5_proto` | `0x154c` | `0x15e4` | **`+0x98`** |
| `__AUTH.__data` | `0x2820` | `0x27a0` | **`-0x80`** |
| `__TEXT.__swift5_reflstr` | `0x3b14` | `0x3b84` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x169b8` | `0x16a20` | **`+0x68`** |
| `__TEXT.__swift5_builtin` | `0x17c` | `0x1a4` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x6d0` | `0x6f8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3760` | `0x3780` | **`+0x20`** |
| `__TEXT.__cstring` | `0x8471` | `0x8451` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0xbb0` | `0xbc8` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x40` | `0x58` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x30f8` | `0x3108` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x11a0` | `0x1194` | **`-0xc`** |
| `__DATA_CONST.__got` | `0xb78` | `0xb80` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5c5c` | `0x5c64` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x7a0` | `0x79c` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x7e0` | `0x7dc` | **`-0x4`** |

### Other Changes

```diff

-816.0.41.0.0
+816.0.47.2.2

-  Functions: 15483
-  Symbols:   7152
-  CStrings:  1362
+  Functions: 15695
+  Symbols:   7210
+  CStrings:  1363
Symbols:
+ _OBJC_CLASS_$_AMSRestrictions
+ _SKServerKeyDialog
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO10CodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOSHAASQ
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO10CodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO10CodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO13AllCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO13AllCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO15FirstCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeO15FirstCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit19AppTransactionQueryV13IterationTypeOSHAASQ
+ _associated conformance 8StoreKit19AppTransactionQueryV4KindO16CachedCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLOSHAASQ
+ _associated conformance 8StoreKit21SKUIEngagementRequestV10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOSHAASQ
+ _associated conformance 8StoreKit21SKUIEngagementRequestV10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO0D16RefundCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOSHAASQ
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO0D16RefundCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO0D16RefundCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOSHAASQ
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO16CustomCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOSHAASQ
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO16CustomCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0G3KeyAAs0F17StringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO16CustomCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0G3KeyAAs0F22DebugStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO20RedeemCodeCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO20RedeemCodeCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO29ManageSubscriptionsCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOSHAASQ
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO29ManageSubscriptionsCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8StoreKit21SKUIEngagementRequestV4KindO29ManageSubscriptionsCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _get_enum_tag_for_layout_string 8StoreKit21SKUIEngagementRequestV4KindO
+ _symbolic SSSg19subscriptionGroupID_t
+ _symbolic _____ 8StoreKit19AppTransactionQueryV13IterationTypeO
+ _symbolic _____ 8StoreKit19AppTransactionQueryV13IterationTypeO10CodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____ 8StoreKit19AppTransactionQueryV13IterationTypeO13AllCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____ 8StoreKit19AppTransactionQueryV13IterationTypeO15FirstCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV4KindO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV4KindO0D16RefundCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV4KindO10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV4KindO16CustomCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV4KindO20RedeemCodeCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____ 8StoreKit21SKUIEngagementRequestV4KindO29ManageSubscriptionsCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____13transactionID_t s6UInt64V
+ _symbolic _____y_____G 8StoreKit11ServiceTaskV AA21SKUIEngagementRequestV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit19AppTransactionQueryV13IterationTypeO10CodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit19AppTransactionQueryV13IterationTypeO13AllCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit19AppTransactionQueryV13IterationTypeO15FirstCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit21SKUIEngagementRequestV10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO0G16RefundCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO16CustomCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO20RedeemCodeCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO29ManageSubscriptionsCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit19AppTransactionQueryV13IterationTypeO10CodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit19AppTransactionQueryV13IterationTypeO13AllCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit19AppTransactionQueryV13IterationTypeO15FirstCodingKeys33_E20F9241F6478C3913B77C9D644A3940LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit21SKUIEngagementRequestV10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO0G16RefundCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO10CodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO16CustomCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO20RedeemCodeCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit21SKUIEngagementRequestV4KindO29ManageSubscriptionsCodingKeys33_76ECC7C06851441D86DD3ECCE2F96D98LLO
+ _type_layout_string 8StoreKit12RedeemOptionV
+ _type_layout_string 8StoreKit21SKUIEngagementRequestV
+ _type_layout_string 8StoreKit21SKUIEngagementRequestV4KindO
- _associated conformance 8StoreKit26OfferCodeRedemptionRequestV10CodingKeys33_974E01167AC5E8883EC5069562A25F93LLOSHAASQ
- _associated conformance 8StoreKit26OfferCodeRedemptionRequestV10CodingKeys33_974E01167AC5E8883EC5069562A25F93LLOs0G3KeyAAs23CustomStringConvertible
- _associated conformance 8StoreKit26OfferCodeRedemptionRequestV10CodingKeys33_974E01167AC5E8883EC5069562A25F93LLOs0G3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 8StoreKit26OfferCodeRedemptionRequestV
- _symbolic _____ 8StoreKit26OfferCodeRedemptionRequestV10CodingKeys33_974E01167AC5E8883EC5069562A25F93LLO
- _symbolic _____y_____G 8StoreKit11ServiceTaskV AA26OfferCodeRedemptionRequestV
- _symbolic _____y_____G s22KeyedDecodingContainerV 8StoreKit26OfferCodeRedemptionRequestV10CodingKeys33_974E01167AC5E8883EC5069562A25F93LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 8StoreKit26OfferCodeRedemptionRequestV10CodingKeys33_974E01167AC5E8883EC5069562A25F93LLO
CStrings:
+ "19:49:07"
+ "Aug  6 2026"
+ "developerErrorCode"
+ "developerErrorMessage"
+ "dialog"
+ "options"
- "05:47:57"
- "Error displaying offer code redemption: "
- "Jul 11 2026"
- "dialog.developerErrorCode"
- "dialog.developerErrorMessage"
```
