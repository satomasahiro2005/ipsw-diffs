## AccountSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/AccountSubscriber.xpc/AccountSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12350` | `0x12784` | **`+0x434`** |
| `__TEXT.__objc_stubs` | `0x1e20` | `0x1f80` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x1b7b` | `0x1c97` | **`+0x11c`** |
| `__TEXT.__cstring` | `0xf3b` | `0x104b` | **`+0x110`** |
| `__DATA_CONST.__cfstring` | `0xbe0` | `0xca0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xaa2` | `0xb0d` | **`+0x6b`** |
| `__DATA.__objc_selrefs` | `0x8b8` | `0x910` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x8a8` | `0x8d8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x3c8` | `0x3f8` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-624.0.8.0.0
+624.0.10.0.0

-  Functions: 279
-  Symbols:   288
-  CStrings:  500
+  Functions: 280
+  Symbols:   300
+  CStrings:  519
Symbols:
+ _AccountPropertyExchangeAllowAppSheet
+ _AccountPropertyExchangeAllowMailRecentsSyncing
+ _AccountPropertyExchangeAllowMove
+ _AccountPropertyExchangeCommunicationServiceRules
+ _AccountPropertyExchangeEnableMailDrop
+ _AccountPropertyExchangeMailNumberOfPastDaysToSync
+ _MFMailAccountRestrictMessageTransfersToOtherAccounts
+ _MFMailAccountRestrictRecentsSyncing
+ _MFMailAccountRestrictSendingFromExternalProcesses
+ _MFMailAccountSupportsMailDrop
+ _OBJC_CLASS_$_MCCommunicationServiceRulesUtilities
+ _OBJC_CLASS_$_NSNull
CStrings:
+ "Invalid CommunicationServiceRules; not applying: %{public}@"
+ "VPNUUID specified (%{public}@) but not applied"
+ "_remotemanagement_exchangeAllowAppSheet"
+ "_remotemanagement_exchangeAllowMailRecentsSyncing"
+ "_remotemanagement_exchangeAllowMove"
+ "_remotemanagement_exchangeCommunicationServiceRules"
+ "_remotemanagement_exchangeEnableMailDrop"
+ "_remotemanagement_exchangeMailNumberOfPastDaysToSync"
+ "null"
+ "payloadAllowAppSheet"
+ "payloadAllowMailRecentsSyncing"
+ "payloadAllowMove"
+ "payloadCommunicationServiceRules"
+ "payloadEnableMailDrop"
+ "payloadMailNumberOfPastDaysToSync"
+ "payloadVPNUUID"
+ "setCommunicationServiceRules:"
+ "setMailNumberOfPastDaysToSync:"
+ "validatedCommunicationServiceRules:outError:"
```
