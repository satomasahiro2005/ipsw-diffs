## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c888` | `0x17cee0` | **`+0x658`** |
| `__TEXT.__oslogstring` | `0xbb7e` | `0xbd15` | **`+0x197`** |
| `__TEXT.__gcc_except_tab` | `0x9480` | `0x94fc` | **`+0x7c`** |
| `__TEXT.__dlopen_cstrs` | `0x526` | `0x4c4` | **`-0x62`** |
| `__AUTH_CONST.__objc_const` | `0x1f780` | `0x1f7c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2bc05` | `0x2bc42` | **`+0x3d`** |
| `__DATA_CONST.__const` | `0x65a8` | `0x65e0` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x23f0` | `0x2410` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x14400` | `0x14420` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1148` | `0x1130` | **`-0x18`** |
| `__DATA.__bss` | `0x1990` | `0x19a0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa4b0` | `0xa4c0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xa808` | `0xa7f8` | **`-0x10`** |
| `__TEXT.__const` | `0xef8` | `0xf08` | **`+0x10`** |
| `__DATA.__data` | `0x1c58` | `0x1c60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5f40` | `0x5f48` | **`+0x8`** |

### Other Changes

```diff

-2459.105.0.0.0
+2465.1.2.0.0

-  Functions: 8858
-  Symbols:   14501
-  CStrings:  8066
+  Functions: 8866
+  Symbols:   14507
+  CStrings:  8075
Symbols:
+ -[CSInlineDonation _errorWithCode:description:underlying:]
+ -[CSSearchQuery didResolveFriendlyAttributeNames:resolvedFetchAttributes:]
+ -[CSSearchQueryContext predicateFrameworkGenerated]
+ -[CSSearchQueryContext predicateSearchToolGenerated]
+ -[CSSearchQueryContext setPredicateFrameworkGenerated:]
+ -[CSSearchQueryContext setPredicateSearchToolGenerated:]
+ GCC_except_table1071
+ GCC_except_table112
+ GCC_except_table119
+ GCC_except_table140
+ GCC_except_table145
+ GCC_except_table161
+ GCC_except_table1645
+ GCC_except_table1651
+ GCC_except_table177
+ GCC_except_table182
+ GCC_except_table186
+ GCC_except_table237
+ GCC_except_table240
+ GCC_except_table259
+ GCC_except_table264
+ GCC_except_table274
+ GCC_except_table279
+ GCC_except_table288
+ GCC_except_table299
+ GCC_except_table325
+ GCC_except_table339
+ GCC_except_table353
+ GCC_except_table358
+ GCC_except_table361
+ GCC_except_table366
+ GCC_except_table368
+ GCC_except_table376
+ GCC_except_table379
+ GCC_except_table382
+ GCC_except_table389
+ GCC_except_table392
+ GCC_except_table394
+ GCC_except_table397
+ GCC_except_table400
+ GCC_except_table474
+ GCC_except_table475
+ GCC_except_table476
+ GCC_except_table477
+ GCC_except_table484
+ GCC_except_table521
+ GCC_except_table568
+ _CSShouldTraceMessagesDonation
+ _PRBuildQueryTree
+ ___74-[CSSearchQuery didResolveFriendlyAttributeNames:resolvedFetchAttributes:]_block_invoke
+ ___block_descriptor_222_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144s152s160w_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8w160l8s104l8s112l8s120l8s128l8s136l8s144l8s152l8
+ ___block_descriptor_40_e8_32s_e41_B24?0"CSTopHitResult"8"NSDictionary"16ls32l8
+ ___block_descriptor_52_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___dropHomeWeakRetrievalItems_block_invoke
+ ___getSSHomeItemBelowRetrievalThresholdsSymbolLoc_block_invoke
+ ___logForCSLogCategoryDonationTracing_block_invoke
+ _getSSHomeItemBelowRetrievalThresholdsSymbolLoc.ptr
+ _logForCSLogCategoryDonationTracing
+ _logForCSLogCategoryDonationTracing.onceToken
+ _logForCSLogCategoryDonationTracing.sDonationTracingLog
+ _objc_retain_x10
+ _sDonationXPCTraceID
- -[CSInlineDonation _logErrorWithCode:description:underlying:]
- -[CSSearchQuery didResolveFriendlyAttributeNames:fromFetchAttributes:]
- -[CSSearchableItemAttributeSet(CSPrivateAttributes) _standardizeProcessorAttributesForBundle:protectionClass:isUpdate:]
- GCC_except_table1072
- GCC_except_table130
- GCC_except_table138
- GCC_except_table143
- GCC_except_table159
- GCC_except_table163
- GCC_except_table1648
- GCC_except_table1654
- GCC_except_table180
- GCC_except_table184
- GCC_except_table244
- GCC_except_table249
- GCC_except_table257
- GCC_except_table262
- GCC_except_table272
- GCC_except_table277
- GCC_except_table290
- GCC_except_table315
- GCC_except_table327
- GCC_except_table349
- GCC_except_table356
- GCC_except_table360
- GCC_except_table362
- GCC_except_table365
- GCC_except_table367
- GCC_except_table371
- GCC_except_table372
- GCC_except_table378
- GCC_except_table380
- GCC_except_table385
- GCC_except_table390
- GCC_except_table393
- GCC_except_table396
- GCC_except_table470
- GCC_except_table471
- GCC_except_table472
- GCC_except_table473
- GCC_except_table480
- GCC_except_table517
- GCC_except_table564
- GCC_except_table742
- _PRBuildDefaultQueryTree
- _PRBuildHomeQueryTree
- _PRBuildMailQueryTree
- _PRBuildMessagesQueryTree
- _PRBuildPhotosQueryTree
- _SpotlightKnowledgeLibraryCore.frameworkLibrary
- ___70-[CSSearchQuery didResolveFriendlyAttributeNames:fromFetchAttributes:]_block_invoke
- ___SpotlightKnowledgeLibraryCore_block_invoke
- ___block_descriptor_209_e8_32s40s48s56s64s72s80s88s96s104s112s120s128s136s144s152w_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8w152l8s96l8s104l8s112l8s120l8s128l8s136l8s144l8
- ___getSKGAttributeProcessorClass_block_invoke
- _audit_stringSpotlightKnowledge
- _getSKGAttributeProcessorClass.softClass
CStrings:
+ "?P"
+ "B24@?0@\"CSTopHitResult\"8@\"NSDictionary\"16"
+ "Completed donation: %@ result: success"
+ "Donation completion block firing, requestID=%u error=%@"
+ "Donation enqueued on CSSearchableIndexRequest, requestID=%u itemCount=%lu"
+ "Donation item manifest, requestID=%u itemIDs=%@"
+ "Donation sending XPC message, requestID=%u donationXPCTraceID=%llu"
+ "Donation unsuccessful: %@ result: %@"
+ "DonationTracing"
+ "MessageIndexing"
+ "NoteIndexing"
+ "SSHomeItemBelowRetrievalThresholds"
+ "[qid=%ld][CSTopHitRanking] bundle=%@ dropped %lu of %lu results below Home retrieval thresholds"
+ "donation-xpc-trace-id"
- "%@: %@ %@"
- "SKGAttributeProcessor"
- "SpotlightKnowledge"
- "SpotlightKnowledgePipelineRefactorStandalone"
- "softlink:r:path:/System/Library/PrivateFrameworks/SpotlightKnowledge.framework/SpotlightKnowledge"
```
