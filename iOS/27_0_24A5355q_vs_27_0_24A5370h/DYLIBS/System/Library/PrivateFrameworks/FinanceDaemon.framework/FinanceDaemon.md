## FinanceDaemon

> `/System/Library/PrivateFrameworks/FinanceDaemon.framework/FinanceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x447214` | `0x4569e4` | **`+0xf7d0`** |
| `__TEXT.__eh_frame` | `0x23cac` | `0x248e8` | **`+0xc3c`** |
| `__TEXT.__oslogstring` | `0x13982` | `0x13ef2` | **`+0x570`** |
| `__AUTH_CONST.__const` | `0xe5a0` | `0xe940` | **`+0x3a0`** |
| `__TEXT.__const` | `0x163b2` | `0x166a2` | **`+0x2f0`** |
| `__TEXT.__unwind_info` | `0xb3d8` | `0xb668` | **`+0x290`** |
| `__DATA.__bss` | `0x13ed0` | `0x14150` | **`+0x280`** |
| `__TEXT.__cstring` | `0xb885` | `0xba95` | **`+0x210`** |
| `__TEXT.__swift5_reflstr` | `0x9524` | `0x9634` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x2364` | `0x2470` | **`+0x10c`** |
| `__TEXT.__swift_as_cont` | `0x1354` | `0x141c` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0x8c0c` | `0x8cca` | **`+0xbe`** |
| `__TEXT.__swift5_fieldmd` | `0x7718` | `0x77c4` | **`+0xac`** |
| `__DATA_CONST.__got` | `0x2a60` | `0x2b08` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `0x7ad8` | `0x7b5c` | **`+0x84`** |
| `__DATA_DIRTY.__data` | `0x5a00` | `0x5a80` | **`+0x80`** |
| `__AUTH.__data` | `0x8ee0` | `0x8f50` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x6628` | `0x6690` | **`+0x68`** |
| `__DATA.__data` | `0x4db8` | `0x4e18` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2028` | `0x2088` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0xa04` | `0xa60` | **`+0x5c`** |
| `__TEXT.__swift_as_entry` | `0x8d8` | `0x92c` | **`+0x54`** |
| `__DATA.__common` | `0xe8` | `0x100` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xcf0` | `0xd08` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x7f4` | `0x804` | **`+0x10`** |

### Other Changes

```diff

-357.2.1.0.0
+362.0.0.0.0

-  Functions: 11403
-  Symbols:   3684
-  CStrings:  2354
+  Functions: 11538
+  Symbols:   3704
+  CStrings:  2389
Symbols:
+ _CSMailboxJunk
+ _CSMailboxTrash
+ _OBJC_CLASS_$_EMMailbox
+ _OBJC_CLASS_$_EMMessage
+ _OBJC_CLASS_$_EMObjectID
+ _OBJC_CLASS_$_NSBatchUpdateResult
+ ___swift_closure_destructor.153Tm
+ ___swift_closure_destructor.195Tm
+ ___swift_closure_destructor.230Tm
+ ___swift_memcpy640_8
+ ___swift_project_boxed_opaque_existential_0Tm
+ _associated conformance 13FinanceDaemon19EmailExistenceError33_BC75C026ED240D2321D3D9C67A9ADA06LLOSHAASQ
+ _associated conformance 13FinanceDaemon29FoundInMailItemDocumentPrunerV15ExistenceSourceOSHAASQ
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic Say_____G______pIeghHrzo_ 10FinanceKit19InstitutionWithPassV s5ErrorP
+ _symbolic ScCyyp______pG s5ErrorP
+ _symbolic Shy_____G 10Foundation3URLV
+ _symbolic _____ 13FinanceDaemon19EmailExistenceError33_BC75C026ED240D2321D3D9C67A9ADA06LLO
+ _symbolic _____ 13FinanceDaemon29ExtractedOrderClustersCleanupO
+ _symbolic _____ 13FinanceDaemon29FoundInMailItemDocumentPrunerV15ExistenceSourceO
+ _symbolic _____ 13FinanceDaemon50PostInstallBackfillLastNotifiedOrderUpdateDateTaskV
+ _symbolic _____8bundleID_SDy__________G25accountIDsWithSharingDatet 10FinanceKit16BundleIdentifierV 10Foundation4UUIDV AA16AccountStartDateV
+ _symbolic _____Sg 13FinanceDaemon23ReceiptAnalyticsTrackerV
+ _symbolic _____SgXw 13FinanceDaemon0bA19StoreImplementationC
+ _symbolic _____SgXwz_Xx 13FinanceDaemon0bA19StoreImplementationC
+ _symbolic _____y_Say_____GG 10FinanceKit0A5StoreC5ReplyO AA19InstitutionWithPassV
+ _type_layout_string 13FinanceDaemon50PostInstallBackfillLastNotifiedOrderUpdateDateTaskV
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.196Tm
- ___swift_closure_destructor.222Tm
- ___swift_memcpy33_8
- ___swift_memcpy600_8
- _swift_release_x11
- _symbolic ShySSGSg
- _type_layout_string 13FinanceDaemon28RecurringPaymentInsightMatch33_DC2D8A6EA272C4F7C06BF0D9D0399425LLV
CStrings:
+ " is not an issuer consent (type: "
+ "\" &&\nkMDItemMailboxes != \""
+ ".prioritizeAllPendingWork"
+ "Added orderEmailBiomeNotificationReceived voucher."
+ "Added prioritizeAllPendingWork voucher."
+ "Backfilled lastNotifiedOrderUpdateDate for %ld extracted orders"
+ "Consent with ID "
+ "Couldn't build a message URL for %s; treating as unknown"
+ "Discarding order email event: invalid mail item. writeTimestamp=%s"
+ "Fetched line item image (%ld bytes), caching in background"
+ "Order Email missing required 'dateSent' writeTimestamp=%s"
+ "Order Email missing required 'fromEmailAddress' writeTimestamp=%s"
+ "Order Email missing required 'messageID' writeTimestamp=%s"
+ "Order Email missing required 'senderDomain' writeTimestamp=%s"
+ "Order Email missing required 'toEmailAddress' writeTimestamp=%s"
+ "Order update date %s has not advanced past last-notified watermark %s, skipping scheduling notifications."
+ "Prewarm: completed line-item image fetch for active extracted orders"
+ "Prewarm: failed to load %s: %@"
+ "Prewarm: fetching %ld line-item images for active extracted orders"
+ "Prewarm: no uncached active extracted-order line-item images to fetch"
+ "Receipts unavailable on this device, skipping receipt instrumentation."
+ "Receipts unavailable on this device, skipping receipt work source."
+ "Scheduled payments fetching is skipped because the last request was done less than `%f` ago."
+ "Scheduled payments requires consent step-up for: %s. Skipping fetch."
+ "Verifying %ld backing email(s) via %s: %ld live, %ld uncertain, %ld to prune"
+ "_createCheckedThrowingContinuation(_:)"
+ "backfillLastNotifiedOrderUpdateDate"
+ "extractedOrder.lineItemImageObjects"
+ "extracted_payment_date_similarity"
+ "has_multi_candidates"
+ "isPendingEntityResolution"
+ "isPendingNormalization"
+ "isPendingReceiptEmailLinking"
+ "kMDItemMailboxes != \""
+ "lastNotifiedOrderUpdateDate"
+ "maild existence check failed for %s; keeping. Error: %@"
+ "merchant_name_similarity"
+ "metadata_timestamp_similarity"
+ "orderContent.orderUpdateDate"
+ "supportedReceiptLinkingRegions"
+ "walletDidForeground: prewarmLineItemImagesForActiveOrders failed: %@"
- "Discarding order email event without messageID. writeTimestamp=%s"
- "Fetched line item image (%ld bytes), caching"
- "FinanceUIService.DaaSUserDiscoveryViewController"
- "Scheduled payments fetching is skipped because the last request was done less than `ManagedPreauthorizedPayment.refreshIntervalSeconds` ago."
- "fine_grained_payment_date"
- "last_four_digits"
```
