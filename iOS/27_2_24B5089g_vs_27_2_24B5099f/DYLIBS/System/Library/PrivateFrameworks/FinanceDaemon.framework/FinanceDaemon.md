## FinanceDaemon

> `/System/Library/PrivateFrameworks/FinanceDaemon.framework/FinanceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x490700` | `0x4a3720` | **`+0x13020`** |
| `__DATA_DIRTY.__data` | `0x6568` | `0x81a8` | **`+0x1c40`** |
| `__DATA.__bss` | `0x143e0` | `0x12d60` | **`-0x1680`** |
| `__DATA_DIRTY.__bss` | `0x3880` | `0x4f00` | **`+0x1680`** |
| `__AUTH.__data` | `0x8fc0` | `0x8090` | **`-0xf30`** |
| `__DATA.__data` | `0x5210` | `0x4748` | **`-0xac8`** |
| `__TEXT.__eh_frame` | `0x26504` | `0x268e8` | **`+0x3e4`** |
| `__TEXT.__const` | `0x17dc2` | `0x17f72` | **`+0x1b0`** |
| `__TEXT.__swift5_reflstr` | `0xa4d4` | `0xa644` | **`+0x170`** |
| `__TEXT.__swift5_typeref` | `0x94f8` | `0x9644` | **`+0x14c`** |
| `__TEXT.__unwind_info` | `0xc2c8` | `0xc408` | **`+0x140`** |
| `__TEXT.__swift5_fieldmd` | `0x8400` | `0x84c8` | **`+0xc8`** |
| `__TEXT.__cstring` | `0xccc5` | `0xcd45` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x25d8` | `0x255c` | **`-0x7c`** |
| `__TEXT.__constg_swiftt` | `0x8218` | `0x8278` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x10768` | `0x10710` | **`-0x58`** |
| `__TEXT.__oslogstring` | `0x149e2` | `0x149a2` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x6a50` | `0x6a80` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x71f0` | `0x71d0` | **`-0x20`** |
| `__DATA.__common` | `0xe0` | `0xc0` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x88` | `0xa8` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x151c` | `0x1500` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f78` | `0x1f90` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x190` | `0x1a4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x994` | `0x980` | **`-0x14`** |
| `__TEXT.__swift5_mpenum` | `0x94` | `0xa4` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x8ac` | `0x8b4` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xad8` | `0xad0` | **`-0x8`** |

### Other Changes

```diff

-376.1.3.0.0
+376.1.5.0.0

-  Functions: 12228
-  Symbols:   3932
+  Functions: 12317
+  Symbols:   3956
Symbols:
+ _get_enum_tag_for_layout_string 13FinanceDaemon23LineItemImageCacheEntry33_39DB1CB21463F037FF889EAE86D27BEALLO
+ _keypath_get_selector_storedOrderUpdateDate
+ _symbolic SS______t 10Foundation4DateV
+ _symbolic Say_____G 10FinanceKit23ExtractedOrderCandidateV7PaymentV11SummaryItemV
+ _symbolic Say_____G 13FinanceDaemon27ExtractedOrderImageSnapshot33_39DB1CB21463F037FF889EAE86D27BEALLV
+ _symbolic Si______SSt 10Foundation4DateV
+ _symbolic So11NSPredicateC
+ _symbolic _____ 10FinanceKit14ExtractedOrderV0A6DaemonE5FuserO2V2V
+ _symbolic _____ 10FinanceKit25ManagedOrderDashboardItemC
+ _symbolic _____ 13FinanceDaemon23LineItemImageCacheEntry33_39DB1CB21463F037FF889EAE86D27BEALLO
+ _symbolic _____ 13FinanceDaemon27ExtractedOrderImageSnapshot33_39DB1CB21463F037FF889EAE86D27BEALLV
+ _symbolic _____4date_Sb9isEnabledt 10Foundation4DateV
+ _symbolic _____4date_Sb9isEnabledtSg 10Foundation4DateV
+ _symbolic _____7insight______16earliestUpcomingt 10FinanceKit43ManagedFinHealthUpcomingTransactionsInsightC AA0cdeF11TransactionC
+ _symbolic _____Sg 10FinanceKit20MerchantCategoryIconV
+ _symbolic _____Sg 10FinanceKit27FinHealthTransactionInsightV20UpcomingTransactionsV
+ _symbolic _____Sg 13FinanceDaemon23LineItemImageCacheEntry33_39DB1CB21463F037FF889EAE86D27BEALLO
+ _symbolic ______SSAAt 10Foundation4DateV
+ _symbolic ______SSt 10Foundation4DateV
+ _symbolic ___________t 10Foundation4DateV AA4UUIDV
+ _symbolic _____ySSSgSay_____GG s18_DictionaryStorageC 10FinanceKit14ExtractedOrderV0C6DaemonE5FuserO0F5EmailV
+ _symbolic _____ySay_____GG s23_ContiguousArrayStorageC 10FinanceKit23ExtractedOrderCandidateV7PaymentV11SummaryItemV
+ _symbolic _____y_____4date_Sb9isEnabledtG s23_ContiguousArrayStorageC 10Foundation4DateV
+ _symbolic _____y_____7insight______16earliestUpcomingtG s23_ContiguousArrayStorageC 10FinanceKit43ManagedFinHealthUpcomingTransactionsInsightC AC0fghI11TransactionC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10FinanceKit20OrderEmailExtractionV8ContentsV8LineItemV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10FinanceKit23ExtractedOrderCandidateV7AddressV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10FinanceKit27FinHealthTransactionInsightV20UpcomingTransactionsV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13FinanceDaemon27ExtractedOrderImageSnapshot33_39DB1CB21463F037FF889EAE86D27BEALLV
+ _type_layout_string 13FinanceDaemon23LineItemImageCacheEntry33_39DB1CB21463F037FF889EAE86D27BEALLO
- _symbolic Shy_____G 10Foundation3URLV
- _symbolic _____ 13FinanceDaemon16AnnotationPrunerV
- _symbolic _____8objectID_SS3keyt 10Foundation4UUIDV
- _symbolic _____8objectID______10annotationSS3keyt 10Foundation4UUIDV AA4DataV
- _type_layout_string 13FinanceDaemon16AnnotationPrunerV
CStrings:
+ "%K == YES AND %K == NO"
+ "Cache hit: line item image previously flagged sensitive, returning nil"
+ "Cluster holds %ld extracted orders, keeping %s. clusterIdentifier=%s, orders=[%s]"
+ "Fetched line item image (%ld bytes), caching"
+ "Line item image flagged as sensitive; caching marker and returning nil"
+ "Prewarm: cached merchant category icon for %s"
+ "Prewarm: failed to cache merchant category icon: %@"
+ "Prewarm: fetching images for %ld active orders if needed"
+ "Prewarm: no active extracted-order images to fetch"
+ "Prewarm: no merchant category icon for %s"
+ "Upcoming Transactions Metrics Tracking: emitting matched event for re-keyed insight %s ('%s'), actual transaction %s"
+ "dashboardItem.storedShowsAsActive"
+ "insightsObject.finHealthInsightObject.finHealthUpcomingTransactionsInsightObject = nil"
+ "upcomingTransactionObjects"
+ "walletDidForeground: prewarmImagesForActiveOrders failed: %@"
- "Could not delete annotation with key %s on object with UUID %s: %@"
- "Deleted %ld orphaned annotations"
- "Deleting annotation with key %s on object with UUID %s."
- "Failed to prune annotations: %@"
- "Fetched line item image (%ld bytes), caching in background"
- "Fetching annotation with key %s on object with UUID %s."
- "Line item image withheld as sensitive"
- "No annotations found. Skipping orphaned annotation pruning."
- "Prewarm: completed line-item image fetch for active extracted orders"
- "Prewarm: fetching %ld line-item images for active extracted orders"
- "Prewarm: no uncached active extracted-order line-item images to fetch"
- "Writing annotation with key %s to object with UUID %s."
- "annotatedObjectID"
- "extractedOrder.lineItemImageObjects"
- "walletDidForeground: prewarmLineItemImagesForActiveOrders failed: %@"
```
