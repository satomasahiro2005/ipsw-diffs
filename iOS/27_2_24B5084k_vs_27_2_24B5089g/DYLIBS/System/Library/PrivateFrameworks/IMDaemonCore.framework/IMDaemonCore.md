## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c1ffc` | `0x3c2f0c` | **`+0xf10`** |
| `__DATA_DIRTY.__objc_data` | `0x3ce8` | `0x4238` | **`+0x550`** |
| `__AUTH_CONST.__objc_const` | `0x276a0` | `0x27aa0` | **`+0x400`** |
| `__AUTH.__objc_data` | `0x3688` | `0x3338` | **`-0x350`** |
| `__DATA.__bss` | `0x58e0` | `0x55e0` | **`-0x300`** |
| `__DATA_DIRTY.__bss` | `0x2910` | `0x2c10` | **`+0x300`** |
| `__DATA_DIRTY.__data` | `0x36e8` | `0x3918` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x55692` | `0x558b2` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x1d694` | `0x1d824` | **`+0x190`** |
| `__TEXT.__cstring` | `0x14306` | `0x14476` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0xe358` | `0xe400` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x1fa18` | `0x1fa78` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x11350` | `0x11390` | **`+0x40`** |
| `__TEXT.__const` | `0x88d8` | `0x8918` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x38d8` | `0x3908` | **`+0x30`** |
| `__AUTH.__data` | `0x718` | `0x6f8` | **`-0x20`** |
| `__DATA.__data` | `0x6d9c` | `0x6dbc` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xad8` | `0xaf8` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0xbb8` | `0xbd0` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0xa6dc` | `0xa6f0` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x368` | `0x378` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x630` | `0x620` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1a0b` | `0x19fb` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2fc0` | `0x2fc8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x133c` | `0x1334` | **`-0x8`** |

### Other Changes

```diff

-1491.200.63.2.1
+1491.200.73.0.0

-  Functions: 15151
-  Symbols:   3289
-  CStrings:  8538
+  Functions: 15200
+  Symbols:   3300
+  CStrings:  8549
Symbols:
+ _IDSCopyIDForTokenWithID
+ _IMServiceCapabilityOneTimeCodesFromUnknownSenders
+ _IMServiceCapabilityTimeSensitiveOneTimeCodes
+ _OBJC_CLASS_$_ABCRemoteDebuggingRequest
+ _OBJC_CLASS_$_ChatRemoteDebuggingDestination
+ _OBJC_CLASS_$_EndpointRemoteDebuggingDestination
+ _OBJC_CLASS_$_ExistingRadarRemoteDebuggingRequest
+ _OBJC_CLASS_$_HandleRemoteDebuggingDestination
+ _OBJC_CLASS_$_IDSEndpoint
+ _OBJC_CLASS_$_NewRadarRemoteDebuggingRequest
+ _OBJC_METACLASS_$_ABCRemoteDebuggingRequest
+ _OBJC_METACLASS_$_ChatRemoteDebuggingDestination
+ _OBJC_METACLASS_$_EndpointRemoteDebuggingDestination
+ _OBJC_METACLASS_$_ExistingRadarRemoteDebuggingRequest
+ _OBJC_METACLASS_$_HandleRemoteDebuggingDestination
+ _OBJC_METACLASS_$_NewRadarRemoteDebuggingRequest
- _OBJC_CLASS_$_IMCTChatBotUtilities
- _OBJC_CLASS_$_IMDNoEligibleDestinationsCache
- _OBJC_CLASS_$_IMDRetryReasonCache
- _OBJC_METACLASS_$_IMDNoEligibleDestinationsCache
- _OBJC_METACLASS_$_IMDRetryReasonCache
CStrings:
+ "/*-------calling into sendRemoteDebuggingRequest: from service that doesn't support it. File a radar-------*/"
+ "IMDaemonCore_Private.ABCRemoteDebuggingRequest"
+ "IMDaemonCore_Private.ChatRemoteDebuggingDestination"
+ "IMDaemonCore_Private.EndpointRemoteDebuggingDestination"
+ "IMDaemonCore_Private.ExistingRadarRemoteDebuggingRequest"
+ "IMDaemonCore_Private.HandleRemoteDebuggingDestination"
+ "IMDaemonCore_Private.NewRadarRemoteDebuggingRequest"
+ "Not applying filter category escalation to one time code in message.guid: %@"
+ "Not inserting group title change item: messageID %@ already stored"
+ "Not tracking one time code in message.guid: %@, service %@ does not track one time codes from unknown senders (known sender: %{BOOL}d)"
+ "Not treating one time code in message.guid: %@ as time sensitive, service %@ does not support time sensitive one time codes"
+ "Queried %lu attachments in the download window, returning %lu with a usable record ID"
+ "Relay status: haveService %{BOOL}d capable %{BOOL}d approved %{BOOL}d"
+ "SMS Relay is remotely approved but no relay IDS service is registered"
- "Does this device have SMS Relay capable devices on its account? %{BOOL}d"
- "Queried %lu attachments, returning %lu after filtering (%lu filtered by date)"
- "Status Of Remote Approval for Relay is %{BOOL}d"
```
