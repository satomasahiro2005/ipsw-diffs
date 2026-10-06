## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39d14` | `0x3aaec` | **`+0xdd8`** |
| `__TEXT.__oslogstring` | `0x6768` | `0x6ae2` | **`+0x37a`** |
| `__TEXT.__objc_stubs` | `0xe80` | `0xf80` | **`+0x100`** |
| `__DATA_CONST.__cfstring` | `0x1780` | `0x1860` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x2050` | `0x20ff` | **`+0xaf`** |
| `__TEXT.__objc_methname` | `0x180b` | `0x1880` | **`+0x75`** |
| `__TEXT.__objc_methlist` | `0x69c` | `0x704` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x5e8` | `0x5f8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x6aa8` | `0x6ab8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xe20` | `0xe30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x720` | `0x728` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x830` | `0x838` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1219.40.7.0.0
+1219.40.10.502.1

-  Functions: 1234
-  Symbols:   2816
-  CStrings:  1264
+  Functions: 1260
+  Symbols:   2838
+  CStrings:  1287
Symbols:
+ -[ACCHWComponentAuthService authenticateBatteryWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateLASWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateTouchControllerWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateTouchControllerWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateVeridianWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateVeridianWithChallenge:completionHandler:updateRegistry:updateUIProperty:logToAnalytics:]
+ -[ACCHWComponentAuthService signRCAMChallenge:completionHandler:]
+ -[ACCHWComponentAuthService signVeridianChallenge:completionHandler:]
+ GCC_except_table79
+ _CFDictionaryCreate
+ __createError
+ _kACCInfo_PPIDVersionUID
+ _kCFACCInfo_PPIDVersionUID
+ _kCFErrorUnderlyingErrorKey
+ _objc_msgSend$authenticateBatteryWithChallenge:completionHandler:componentIndex:
+ _objc_msgSend$authenticateLASWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$authenticateRCAMWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$authenticateTouchControllerWithChallenge:completionHandler:updateRegistry:componentIndex:
+ _objc_msgSend$authenticateVeridianWithChallenge:completionHandler:componentIndex:
+ _objc_msgSend$signRCAMChallenge:completionHandler:componentIndex:
+ _objc_msgSend$signVeridianChallenge:completionHandler:componentIndex:
+ _objc_msgSend$verifyModuleCertificate:forModule:forAuthFlags:forIndex:
- GCC_except_table72
CStrings:
+ "%s: !sendOutgoingHandler"
+ "%s: authSession(%d), keepOpen %d, error %d"
+ "PPIDVersionUID"
+ "authSetupStart: initMessage_RequestAuthSetup failed: %d"
+ "authenticateTouchControllerWithChallenge:completionHandler:"
+ "com.apple.mfi4Auth.decrypt"
+ "com.apple.mfi4Auth.encrypt"
+ "com.apple.mfi4Auth.process"
+ "com.apple.mfi4Auth.protocol"
+ "com.apple.mfi4Auth.receive"
+ "com.apple.mfi4Auth.send"
+ "decryptIncomingData: decryptPayload rc=%d"
+ "decryptIncomingData: failed: %d"
+ "encryptOutgoingData: encryptPayload rc=%d"
+ "failed to handle refresh access state response"
+ "mfi4Auth_protocol_handle_AuthCert: Accessory did NOT provide PrivacyPrefix!"
+ "mfi4Auth_protocol_processIncomingMessage: error: %d"
+ "mfi4Auth_protocol_processIncomingMessageExtra: error: %d"
+ "processIncomingMessageExtra: non-Extra message id 0x%04x — falling through to relay"
+ "processIncomingMessageRelay: error: %d"
+ "processIncomingMessageRelay: non-relay message id 0x%04x — no relay action"
+ "processOutgoingSecureTunnelDataForClient: sendOutgoingData failed"
+ "publicManufacturerNVMRead: initMessage_RequestManufacturerNVMRead failed: %d"
+ "receiveIncomingData: sendOutgoingData failed"
+ "requestRefreshAccessState: !authSession"
+ "requestRefreshAccessState: !outMessage"
+ "requestRefreshAccessState: authSession shutting down"
+ "requestRefreshAccessState: initMessage_RequestRefreshAccessState failed: %d"
+ "userNVMRead: initMessage_RequestUserNVMRead failed: %d"
+ "userNVMWrite: initMessage_RequestUserNVMWrite failed: %d"
+ "verifyModuleCertificate:forModule:forAuthFlags:forIndex:"
- "%s: authSession(%d), keepOpen %d"
- "Data not passed in"
- "decryptIncomingData: failed"
- "encryptOutgoingData: encryptPayload: error: %d"
- "failed to handle auth failed"
- "mfi4Auth_protocol_processIncomingMessage: error"
- "mfi4Auth_protocol_processIncomingMessageExtra: error"
- "processIncomingMessageRelay: error"
```
