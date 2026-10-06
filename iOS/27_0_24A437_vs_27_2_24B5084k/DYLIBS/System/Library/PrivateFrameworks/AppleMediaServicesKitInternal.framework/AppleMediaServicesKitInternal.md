## AppleMediaServicesKitInternal

> `/System/Library/PrivateFrameworks/AppleMediaServicesKitInternal.framework/AppleMediaServicesKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x614fd8` | `0x5f00dc` | **`-0x24efc`** |
| `__TEXT.__gcc_except_tab` | `0x2dbc0` | `0x2b9b8` | **`-0x2208`** |
| `__TEXT.__const` | `0x54370` | `0x52c08` | **`-0x1768`** |
| `__AUTH_CONST.__const` | `0x27960` | `0x27058` | **`-0x908`** |
| `__TEXT.__unwind_info` | `0xda20` | `0xd398` | **`-0x688`** |
| `__TEXT.__cstring` | `0xdf5d` | `0xde99` | **`-0xc4`** |
| `__AUTH_CONST.__cfstring` | `0x640` | `0x660` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1488` | `0x1498` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1d50` | `0x1d60` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa50` | `0xa60` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x660` | `0x658` | **`-0x8`** |

### Other Changes

```diff

-2.0.29.0.0
+2.1.4.0.0

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 10755
-  Symbols:   668
-  CStrings:  2123
+  Functions: 10514
+  Symbols:   669
+  CStrings:  2094
Symbols:
+ _MGCopyAnswerWithError
+ _OBJC_CLASS_$_MCProfileConnection
+ _dispatch_queue_set_specific
+ _dispatch_sync
- __DefaultRuneLocale
- __ZNSt3__17codecvtIDiDu11__mbstate_tE2idE
- ___maskrune
CStrings:
+ "-seed"
+ "2.1.4"
+ "AMSAcknowledgePrivacyOverride"
+ "Account was resolved as null."
+ "Failed to create privacy override provider. error = "
+ "Failed to encode character: "
+ "Failed to encode invalid UTF-8."
+ "Failed to obtain hardware platform: "
+ "HTTP/1.1"
+ "HardwarePlatform"
+ "No account was resolved for the identity the bag was created with, so it will be used as is."
+ "Resolving the account the bag was created with failed, so it will be used as is. "
+ "accountRemoveFailed"
+ "com.apple.MediaServices.AppleSchedulingProvider"
+ "getStatus: privacy acknowledgement override is `always`, returning Status::none"
+ "getStatus: privacy acknowledgement override is `disabled`, returning Status::acceptedCurrent"
+ "invalid_utf8"
+ "streaming_unsupported"
- " ("
- " FW/"
- " build/"
- " maker/"
- " model/"
- ")>"
- "2.0.29"
- "Backoff blocking outgoing request"
- "Detected long backoff time, clamping"
- "Error parsing IdMS storm headers"
- "Failed to decode UTF-8 character from string."
- "Failed to encode character with value: "
- "Location"
- "Rejecting request based on backoff policy."
- "Response"
- "Unknown IdMS service, skipping backoff..."
- "X-Apple-I-88CC-99DE-EE63-2736"
- "X-Apple-I-Client-Bundle-Id"
- "X-Apple-I-MD"
- "X-Apple-I-MD-M"
- "X-Apple-I-MD-RInfo"
- "X-Apple-I-Proxied-Bundle-Id"
- "X-Apple-I-Stable-Id"
- "X-Apple-S-Backoff"
- "X-Apple-S-Backoff-Server-Info"
- "X-AppleId-Device-UDID"
- "X-MME-Device-Id"
- "X-MMe-Client-Info"
- "b"
- "c"
- "com.AppleMediaServices.AppleSchedulingProvider"
- "com.apple.AuthKitAndroid"
- "com.apple.MediaServices.AppleSchedulingProvider.delayed"
- "com.apple.gs.idms.hb"
- "i"
- "midFinishProvisioning"
- "midStartProvisioning"
- "midSyncMachine"
- "missing SPIM"
- "missing key "
- "missing ptm"
- "missing response"
- "missing tk"
- "p"
- "ptm"
- "spim"
- "tk"
```
