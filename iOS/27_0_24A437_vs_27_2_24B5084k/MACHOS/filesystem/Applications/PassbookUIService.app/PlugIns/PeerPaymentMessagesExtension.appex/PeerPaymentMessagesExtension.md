## PeerPaymentMessagesExtension

> `/Applications/PassbookUIService.app/PlugIns/PeerPaymentMessagesExtension.appex/PeerPaymentMessagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11ce8` | `0x12160` | **`+0x478`** |
| `__TEXT.__objc_methname` | `0x3a73` | `0x3bc1` | **`+0x14e`** |
| `__TEXT.__objc_stubs` | `0x39e0` | `0x3b20` | **`+0x140`** |
| `__DATA.__objc_selrefs` | `0x10b8` | `0x1108` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x18d5` | `0x18fd` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x518` | `0x508` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x6f0` | `0x700` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x420` | `0x430` | **`+0x10`** |
| `__DATA.__objc_const` | `0x898` | `0x890` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x388` | `0x390` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x9b0` | `0x9b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1695.1.4.0.0
+1696.2.5.0.0

-  Functions: 262
-  Symbols:   291
-  CStrings:  901
+  Functions: 264
+  Symbols:   290
+  CStrings:  912
Symbols:
+ _objc_opt_respondsToSelector
- _PKAnalyticsReportPeerPaymentBillSplitContextSplitTypeEqualSplit
- _PKAnalyticsReportPeerPaymentBillSplitContextSplitTypeItemize
CStrings:
+ "Inserted payment as reply, didThread=%d"
+ "_insertMessage:replyingToMessage:completion:"
+ "_updateAnalyticsContextForConfiguration:"
+ "archivedSessionTokenForSubject:"
+ "billSplitContextWithReceiptRequestType:receiptLength:"
+ "effectiveSenderAddress"
+ "insertMessage:replyingToMessage:completionHandler:"
+ "primaryAppController"
+ "receiptLineItemCount"
+ "setAnalyticsBillSplitContext:"
+ "setAnalyticsMessagesContext:"
+ "setAnalyticsSessionToken:"
+ "setTransactionSourceIdentifiers:"
- "_insertMessage:completion:"
- "billSplitContextWithSplitType:receiptLength:"
```
