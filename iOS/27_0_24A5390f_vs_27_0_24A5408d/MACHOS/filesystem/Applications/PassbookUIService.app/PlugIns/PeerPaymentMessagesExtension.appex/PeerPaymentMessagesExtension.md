## PeerPaymentMessagesExtension

> `/Applications/PassbookUIService.app/PlugIns/PeerPaymentMessagesExtension.appex/PeerPaymentMessagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a44` | `0x11ce8` | **`+0x2a4`** |
| `__TEXT.__objc_methname` | `0x3985` | `0x3a73` | **`+0xee`** |
| `__TEXT.__objc_stubs` | `0x3900` | `0x39e0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x154d` | `0x15a3` | **`+0x56`** |
| `__DATA_CONST.__cfstring` | `0xf40` | `0xf80` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1088` | `0x10b8` | **`+0x30`** |
| `__DATA.__objc_const` | `0x878` | `0x898` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x998` | `0x9b0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x510` | `0x518` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x428` | `0x420` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x68` | `0x6c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1689.3.0.0.0
+1695.1.2.0.0

-  Functions: 260
-  Symbols:   289
-  CStrings:  892
+  Functions: 262
+  Symbols:   291
+  CStrings:  901
Symbols:
+ _MSMessagesErrorDomain
+ __Z35PKLocalizedPeerPaymentReceiptStringP8NSString
CStrings:
+ "PEER_PAYMENT_RECEIPT_TOO_LONG_ERROR_MESSAGE"
+ "PEER_PAYMENT_RECEIPT_TOO_LONG_ERROR_TITLE"
+ "_activeSendPeerPaymentController"
+ "_hasStagedUnsentBubbleMessage"
+ "_persistPendingRequestForMessage:localProperties:"
+ "_presentAlertWithTitle:message:buttonTitle:image:completion:"
+ "hasReceiptDetails"
+ "receiptRequestAmount"
+ "setReceiptRequestAmount:"
```
