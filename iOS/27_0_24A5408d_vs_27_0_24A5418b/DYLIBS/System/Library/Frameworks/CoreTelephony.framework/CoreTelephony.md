## CoreTelephony

> `/System/Library/Frameworks/CoreTelephony.framework/CoreTelephony`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d38d4` | `0x1d02d8` | **`-0x35fc`** |
| `__AUTH_CONST.__objc_const` | `0x37590` | `0x36fd0` | **`-0x5c0`** |
| `__TEXT.__oslogstring` | `0x54c6` | `0x50a6` | **`-0x420`** |
| `__TEXT.__gcc_except_tab` | `0x25910` | `0x254fc` | **`-0x414`** |
| `__TEXT.__objc_methlist` | `0x1facc` | `0x1f7ec` | **`-0x2e0`** |
| `__TEXT.__unwind_info` | `0x11020` | `0x10e28` | **`-0x1f8`** |
| `__AUTH.__objc_data` | `0xd340` | `0xd1b0` | **`-0x190`** |
| `__TEXT.__cstring` | `0x21fe8` | `0x21e78` | **`-0x170`** |
| `__AUTH_CONST.__cfstring` | `0x20bc0` | `0x20b20` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x78f0` | `0x7858` | **`-0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x88c0` | `0x8880` | **`-0x40`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d58` | `0x1d28` | **`-0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x1978` | `0x1950` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x2738` | `0x2718` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xc58` | `0xc38` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x12e8` | `0x12c8` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xf88` | `0xf70` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x16bc` | `0x16ac` | **`-0x10`** |

### Other Changes

```diff

-13487.3.0.0.0
+13487.6.0.0.0

-  Functions: 13094
-  Symbols:   24174
-  CStrings:  6527
+  Functions: 13021
+  Symbols:   24053
+  CStrings:  6483
Symbols:
- +[CTStewieAnywhereMessage supportsSecureCoding]
- +[CTStewieDiagMessage supportsSecureCoding]
- +[CTStewieIMessageLiteRawMessage supportsSecureCoding]
- +[CTStewieSatSmsRawMessage supportsSecureCoding]
- +[CTXPCFakeCrossPlatformEventRequest allowedClassesForArguments]
- -[CTStewieAnywhereMessage .cxx_destruct]
- -[CTStewieAnywhereMessage copyWithZone:]
- -[CTStewieAnywhereMessage data]
- -[CTStewieAnywhereMessage description]
- -[CTStewieAnywhereMessage encodeWithCoder:]
- -[CTStewieAnywhereMessage initWithCoder:]
- -[CTStewieAnywhereMessage isEqual:]
- -[CTStewieAnywhereMessage isEqualToAnywhereMessage:]
- -[CTStewieAnywhereMessage setData:]
- -[CTStewieDiagMessage .cxx_destruct]
- -[CTStewieDiagMessage copyWithZone:]
- -[CTStewieDiagMessage data]
- -[CTStewieDiagMessage description]
- -[CTStewieDiagMessage encodeWithCoder:]
- -[CTStewieDiagMessage initWithCoder:]
- -[CTStewieDiagMessage isEqual:]
- -[CTStewieDiagMessage isEqualToDiagMessage:]
- -[CTStewieDiagMessage setData:]
- -[CTStewieIMessageLiteRawMessage .cxx_destruct]
- -[CTStewieIMessageLiteRawMessage copyWithZone:]
- -[CTStewieIMessageLiteRawMessage data]
- -[CTStewieIMessageLiteRawMessage description]
- -[CTStewieIMessageLiteRawMessage encodeWithCoder:]
- -[CTStewieIMessageLiteRawMessage initWithCoder:]
- -[CTStewieIMessageLiteRawMessage isEqual:]
- -[CTStewieIMessageLiteRawMessage isEqualToOther:]
- -[CTStewieIMessageLiteRawMessage setData:]
- -[CTStewieSatSmsRawMessage .cxx_destruct]
- -[CTStewieSatSmsRawMessage copyWithZone:]
- -[CTStewieSatSmsRawMessage data]
- -[CTStewieSatSmsRawMessage description]
- -[CTStewieSatSmsRawMessage encodeWithCoder:]
- -[CTStewieSatSmsRawMessage initWithCoder:]
- -[CTStewieSatSmsRawMessage isEqual:]
- -[CTStewieSatSmsRawMessage isEqualToOther:]
- -[CTStewieSatSmsRawMessage setData:]
- -[CTXPCFakeCrossPlatformEventRequest eventName]
- -[CTXPCFakeCrossPlatformEventRequest initWithEvent:payload:]
- -[CTXPCFakeCrossPlatformEventRequest payload]
- -[CTXPCFakeCrossPlatformEventRequest performRequestWithHandler:completionHandler:]
- -[CTXPCFakeCrossPlatformEventRequest requiredEntitlement]
- -[CoreTelephonyClient(CrossPlatformTransfer) fakeCrossPlatformTransferEvent:payload:completion:]
- -[CoreTelephonyClient(Provisioning) invalidateKey:]
- -[CoreTelephonyClient(SMS) injectMTsms:smsData:completion:]
- _OBJC_CLASS_$_CTStewieAnywhereMessage
- _OBJC_CLASS_$_CTStewieDiagMessage
- _OBJC_CLASS_$_CTStewieIMessageLiteRawMessage
- _OBJC_CLASS_$_CTStewieSatSmsRawMessage
- _OBJC_CLASS_$_CTXPCFakeCrossPlatformEventRequest
- _OBJC_IVAR_$_CTStewieAnywhereMessage._data
- _OBJC_IVAR_$_CTStewieDiagMessage._data
- _OBJC_IVAR_$_CTStewieIMessageLiteRawMessage._data
- _OBJC_IVAR_$_CTStewieSatSmsRawMessage._data
- _OBJC_METACLASS_$_CTStewieAnywhereMessage
- _OBJC_METACLASS_$_CTStewieDiagMessage
- _OBJC_METACLASS_$_CTStewieIMessageLiteRawMessage
- _OBJC_METACLASS_$_CTStewieSatSmsRawMessage
- _OBJC_METACLASS_$_CTXPCFakeCrossPlatformEventRequest
- _OUTLINED_FUNCTION_9
- _TelephonyUtilIsOversteerEnabled
- __OBJC_$_CLASS_METHODS_CTStewieAnywhereMessage
- __OBJC_$_CLASS_METHODS_CTStewieDiagMessage
- __OBJC_$_CLASS_METHODS_CTStewieIMessageLiteRawMessage
- __OBJC_$_CLASS_METHODS_CTStewieSatSmsRawMessage
- __OBJC_$_CLASS_METHODS_CTXPCFakeCrossPlatformEventRequest
- __OBJC_$_CLASS_PROP_LIST_CTStewieAnywhereMessage
- __OBJC_$_CLASS_PROP_LIST_CTStewieDiagMessage
- __OBJC_$_CLASS_PROP_LIST_CTStewieIMessageLiteRawMessage
- __OBJC_$_CLASS_PROP_LIST_CTStewieSatSmsRawMessage
- __OBJC_$_INSTANCE_METHODS_CTStewieAnywhereMessage
- __OBJC_$_INSTANCE_METHODS_CTStewieDiagMessage
- __OBJC_$_INSTANCE_METHODS_CTStewieIMessageLiteRawMessage
- __OBJC_$_INSTANCE_METHODS_CTStewieSatSmsRawMessage
- __OBJC_$_INSTANCE_METHODS_CTXPCFakeCrossPlatformEventRequest
- __OBJC_$_INSTANCE_VARIABLES_CTStewieAnywhereMessage
- __OBJC_$_INSTANCE_VARIABLES_CTStewieDiagMessage
- __OBJC_$_INSTANCE_VARIABLES_CTStewieIMessageLiteRawMessage
- __OBJC_$_INSTANCE_VARIABLES_CTStewieSatSmsRawMessage
- __OBJC_$_PROP_LIST_CTStewieAnywhereMessage
- __OBJC_$_PROP_LIST_CTStewieDiagMessage
- __OBJC_$_PROP_LIST_CTStewieIMessageLiteRawMessage
- __OBJC_$_PROP_LIST_CTStewieSatSmsRawMessage
- __OBJC_CLASS_PROTOCOLS_$_CTStewieAnywhereMessage
- __OBJC_CLASS_PROTOCOLS_$_CTStewieDiagMessage
- __OBJC_CLASS_PROTOCOLS_$_CTStewieIMessageLiteRawMessage
- __OBJC_CLASS_PROTOCOLS_$_CTStewieSatSmsRawMessage
- __OBJC_CLASS_RO_$_CTStewieAnywhereMessage
- __OBJC_CLASS_RO_$_CTStewieDiagMessage
- __OBJC_CLASS_RO_$_CTStewieIMessageLiteRawMessage
- __OBJC_CLASS_RO_$_CTStewieSatSmsRawMessage
- __OBJC_CLASS_RO_$_CTXPCFakeCrossPlatformEventRequest
- __OBJC_METACLASS_RO_$_CTStewieAnywhereMessage
- __OBJC_METACLASS_RO_$_CTStewieDiagMessage
- __OBJC_METACLASS_RO_$_CTStewieIMessageLiteRawMessage
- __OBJC_METACLASS_RO_$_CTStewieSatSmsRawMessage
- __OBJC_METACLASS_RO_$_CTXPCFakeCrossPlatformEventRequest
- __ZL17logBlockedRequestPKcRKN3xpc4dictEP20__CTServerConnection20CTFeatureRequirement
- __ZZN8dispatch5asyncIZN9CCMonitor10initializeEvE3$_1EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
- __ZZN8dispatch5asyncIZZN9CCMonitor10initializeEvEUb_E3$_0EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
- __ZZN9CCMonitor9getLoggerEvE10sOnceToken
- __ZZN9CCMonitor9getLoggerEvE7sLogger
- ___51-[CoreTelephonyClient(Provisioning) invalidateKey:]_block_invoke
- ___51-[CoreTelephonyClient(Provisioning) invalidateKey:]_block_invoke_2
- ___55-[CoreTelephonyClient(Stewie) testStewieCommand:error:]_block_invoke
- ___55-[CoreTelephonyClient(Stewie) testStewieCommand:error:]_block_invoke_2
- ___59-[CoreTelephonyClient(SMS) injectMTsms:smsData:completion:]_block_invoke
- ___60-[CoreTelephonyClient(Stewie) testStewieCommand:completion:]_block_invoke
- ___82-[CTXPCFakeCrossPlatformEventRequest performRequestWithHandler:completionHandler:]_block_invoke
- ___96-[CoreTelephonyClient(CrossPlatformTransfer) fakeCrossPlatformTransferEvent:payload:completion:]_block_invoke
- ___96-[CoreTelephonyClient(CrossPlatformTransfer) fakeCrossPlatformTransferEvent:payload:completion:]_block_invoke_2
- ____ZN9CCMonitor10initializeEv_block_invoke
- ____ZN9CCMonitor9getLoggerEv_block_invoke
- ___block_descriptor_48_e8_32r40r_e34_v24?0"NSError"8"NSDictionary"16lr32l8r40l8
- _kCTStewieDiagDataKey
- _notify_get_state
- _notify_register_dispatch
CStrings:
+ "13487.6"
+ "13487.6~5"
+ "notSupportedInBuddy"
- ", epki=%@, shared=%@"
- "13487.3"
- "13487.3~40"
- "Available features: [%s]"
- "Blocking %s (request: '%s', state: %s, required: %s, %p)"
- "Body:"
- "CTStewieRequestReasonAnywhere"
- "CTStewieRequestReasonAnywhereTest"
- "CTStewieRequestReasonTest"
- "CommCenter is always-on. CCMonitor is NOT used"
- "Communication blocked but cached value found. Request: '%s'. Reply: '%s'"
- "CoreTelephony logging is %s by default"
- "Daemon becomes ready..."
- "DataLen = %u"
- "Failed to create notify token for '%s'. Logging is %s by default"
- "Failed to re-register notifications in _HandleConnectionReEstablished(). Error: {domain=%d, error=%d}"
- "Failed to re-register notifications in _HandlePrepWorkBeforeSend(). Error: {domain=%d, error=%d}"
- "HeadersLen = %u"
- "Logging is %s"
- "OS log created"
- "Part %u"
- "ReregisterClientForAllEvents request is not allowed at this time. Registration is delayed"
- "XPC message"
- "XPC message with reply"
- "_CTServerConnectionGetCommCenterInitializationState request is not allowed at this time"
- "_CTServerConnectionRegisterForEvent request is not allowed at this time. Registration is delayed"
- "_CTServerConnectionUnregisterForAllNotifications request is not allowed at this time"
- "_CTServerConnectionUnregisterForEvent request is not allowed at this time"
- "async XPC message"
- "com.apple.CoreTelephony.LoggingEnabled"
- "diagData"
- "epki"
- "event"
- "feth"
- "kBaseband"
- "kDaemonRunning"
- "kDefaultAllowed"
- "kNotRunning"
- "kRunning"
- "kTestBlocked"
- "kThumper"
- "kUnknown"
- "nEntries = %u"
- "pdp_ip"
- "shared"
- "v12@?0i8"
- "v24@?0@\"NSError\"8@\"NSDictionary\"16"
```
