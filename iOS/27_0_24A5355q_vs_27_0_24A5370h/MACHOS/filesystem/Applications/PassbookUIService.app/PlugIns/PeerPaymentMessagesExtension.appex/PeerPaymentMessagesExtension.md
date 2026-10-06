## PeerPaymentMessagesExtension

> `/Applications/PassbookUIService.app/PlugIns/PeerPaymentMessagesExtension.appex/PeerPaymentMessagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11370` | `0x114ac` | **`+0x13c`** |
| `__TEXT.__cstring` | `0x14eb` | `0x1540` | **`+0x55`** |
| `__TEXT.__objc_methname` | `0x3921` | `0x3908` | **`-0x19`** |
| `__DATA_CONST.__const` | `0xc48` | `0xc60` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x6f0` | `0x6e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x9a8` | `0x998` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x388` | `0x380` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x508` | `0x510` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1677.4.0.0.0
+1682.1.0.0.0
Symbols:
+ _PKLegacyWalletURLScheme
- __Z35PKLocalizedPeerPaymentReceiptStringP8NSString
CStrings:
+ "%@://card/%@"
+ "PEER_PAYMENT_RESPOND_TO_PAYMENT_REQUEST_ENABLEMENT_REQUIRED_ALERT_ACTION_CANCEL"
+ "PEER_PAYMENT_RESPOND_TO_PAYMENT_REQUEST_ENABLEMENT_REQUIRED_ALERT_ACTION_SETTINGS"
+ "PEER_PAYMENT_RESPOND_TO_PAYMENT_REQUEST_ENABLEMENT_REQUIRED_ALERT_MESSAGE"
+ "PEER_PAYMENT_RESPOND_TO_PAYMENT_REQUEST_ENABLEMENT_REQUIRED_ALERT_TITLE"
+ "setHideBillSplitButton:"
- "PEER_PAYMENT_RECEIPT_BUBBLE_UNAVAILABLE_ALERT_BUTTON_TITLE"
- "PEER_PAYMENT_RECEIPT_BUBBLE_UNAVAILABLE_ALERT_MESSAGE"
- "PEER_PAYMENT_RECEIPT_BUBBLE_UNAVAILABLE_ALERT_TITLE"
- "PKPeerPaymentMessagesActionShowReceiptRequestDetails"
- "_showReceiptRequestDetailsForMessage:completion:"
- "shoebox://card/%@"
```
