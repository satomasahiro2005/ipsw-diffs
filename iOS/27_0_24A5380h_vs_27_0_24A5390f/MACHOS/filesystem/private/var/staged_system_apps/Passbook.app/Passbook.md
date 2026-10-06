## Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10008` | `0x100c4` | **`+0xbc`** |
| `__TEXT.__objc_methname` | `0x4725` | `0x4779` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x4ec` | `0x53e` | **`+0x52`** |
| `__DATA_CONST.__const` | `0x920` | `0x940` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2f00` | `0x2f20` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xf98` | `0xfa8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xfd0` | `0xfd8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x918` | `0x920` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1686.3.0.0.0
+1689.3.0.0.0

-  Functions: 198
-  Symbols:   401
-  CStrings:  783
+  Functions: 199
+  Symbols:   402
+  CStrings:  785
Symbols:
+ _OBJC_CLASS_$_PKFinanceKitForegroundHook
CStrings:
+ "PBKSceneDelegate: PKFinanceKitForegroundHook notifyWalletDidForeground failed: %@"
+ "notifyWalletDidForegroundWithCompletionHandler:"
+ "presentBillSplitWithImage:receiptData:recipientAddresses:conversationIdentifier:sessionIdentifier:mode:completion:"
+ "presentPeerPaymentBillSplitWithImage:receiptData:recipientAddresses:conversationIdentifier:sessionIdentifier:mode:"
+ "v72@0:8@\"UIImage\"16@\"NSData\"24@\"NSArray\"32@\"NSString\"40@\"NSString\"48q56@?<v@?B>64"
+ "v72@0:8@16@24@32@40@48q56@?64"
- "presentBillSplitWithImage:receiptData:recipientAddresses:conversationIdentifier:mode:completion:"
- "presentPeerPaymentBillSplitWithImage:receiptData:recipientAddresses:conversationIdentifier:mode:"
- "v64@0:8@\"UIImage\"16@\"NSData\"24@\"NSArray\"32@\"NSString\"40q48@?<v@?B>56"
- "v64@0:8@16@24@32@40q48@?56"
```
