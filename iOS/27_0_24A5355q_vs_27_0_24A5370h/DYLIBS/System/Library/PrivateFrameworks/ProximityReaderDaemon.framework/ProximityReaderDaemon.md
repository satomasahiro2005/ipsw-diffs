## ProximityReaderDaemon

> `/System/Library/PrivateFrameworks/ProximityReaderDaemon.framework/ProximityReaderDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5390` | `0x1ea7cc` | **`+0x543c`** |
| `__TEXT.__unwind_info` | `0x5c40` | `0x61a0` | **`+0x560`** |
| `__AUTH_CONST.__const` | `0xd4f0` | `0xd9a8` | **`+0x4b8`** |
| `__TEXT.__const` | `0xd8b4` | `0xdc04` | **`+0x350`** |
| `__AUTH_CONST.__objc_const` | `0x7a58` | `0x7d58` | **`+0x300`** |
| `__TEXT.__eh_frame` | `0xde50` | `0xe148` | **`+0x2f8`** |
| `__AUTH.__data` | `0x6150` | `0x6380` | **`+0x230`** |
| `__DATA.__bss` | `0x11dd0` | `0x11fd0` | **`+0x200`** |
| `__TEXT.__swift5_capture` | `0x2efc` | `0x30d8` | **`+0x1dc`** |
| `__TEXT.__swift5_reflstr` | `0x4a03` | `0x4ba3` | **`+0x1a0`** |
| `__TEXT.__constg_swiftt` | `0x53f8` | `0x5584` | **`+0x18c`** |
| `__TEXT.__swift5_fieldmd` | `0x5470` | `0x55b0` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x3a9c` | `0x3b4c` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0xb61b` | `0xb6ab` | **`+0x90`** |
| `__TEXT.__swift_as_cont` | `0xa58` | `0xad8` | **`+0x80`** |
| `__TEXT.__swift_as_entry` | `0x510` | `0x548` | **`+0x38`** |
| `__TEXT.__cstring` | `0x7a04` | `0x79d4` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0xdb0` | `0xde0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x3188` | `0x31b0` | **`+0x28`** |
| `__DATA.__data` | `0x20c8` | `0x20f0` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x584` | `0x5a4` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x360` | `0x378` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x8ec` | `0x900` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x308` | `0x318` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x564` | `0x574` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x14f8` | `0x1500` | **`+0x8`** |
| `__DATA.__common` | `0x4e0` | `0x4e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xda0` | `0xd98` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-150.26.1.0.0
+150.28.1.0.0

+  - /System/Library/Frameworks/CoreNFC.framework/CoreNFC

-  Functions: 6587
-  Symbols:   2448
+  Functions: 6717
+  Symbols:   2470
Symbols:
+ _OBJC_CLASS_$_NFCNDEFReaderSession
+ __DATA__TtC21ProximityReaderDaemon17InactivityMonitor
+ __DATA__TtC21ProximityReaderDaemon27EngagementCapabilityChecker
+ __IVARS__TtC21ProximityReaderDaemon17InactivityMonitor
+ __IVARS__TtC21ProximityReaderDaemon27EngagementCapabilityChecker
+ __METACLASS_DATA__TtC21ProximityReaderDaemon17InactivityMonitor
+ __METACLASS_DATA__TtC21ProximityReaderDaemon27EngagementCapabilityChecker
+ __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore34EngagementCustomerServiceInterface_
+ __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore34EngagementMerchantServiceInterface_
+ __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore34EngagementCustomerServiceInterface_
+ __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore34EngagementMerchantServiceInterface_
+ __PROTOCOL__TtP19ProximityReaderCore34EngagementCustomerServiceInterface_
+ __PROTOCOL__TtP19ProximityReaderCore34EngagementMerchantServiceInterface_
+ ___swift_closure_destructor.103Tm
+ ___swift_closure_destructor.54Tm
+ _associated conformance 21ProximityReaderDaemon26EngagementCapabilityResultO7FailureOSHAASQ
+ _symbolic $s21ProximityReaderDaemon28EngagementCapabilityCheckingP
+ _symbolic Iegh_
+ _symbolic Sbyc
+ _symbolic ScCy_____y__________G_____G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon17BrandDataResponseV 0bC4Core19EngagementErrorTypeO s5NeverO
+ _symbolic ScCy_____y__________G_____G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon24BrandDataRefreshResponseV 0bC4Core19EngagementErrorTypeO s5NeverO
+ _symbolic _____ 21ProximityReaderDaemon17InactivityMonitorC
+ _symbolic _____ 21ProximityReaderDaemon26EngagementCapabilityResultO
+ _symbolic _____ 21ProximityReaderDaemon26EngagementCapabilityResultO7FailureO
+ _symbolic _____ 21ProximityReaderDaemon27EngagementCapabilityCheckerC
+ _symbolic _____ s8DurationV
+ _symbolic _____Sg 21ProximityReaderDaemon17InactivityMonitorC
+ _symbolic _____SgXw 21ProximityReaderDaemon17InactivityMonitorC
+ _symbolic _____SgXwz_Xx 21ProximityReaderDaemon17InactivityMonitorC
+ _symbolic ______p 21ProximityReaderDaemon28EngagementCapabilityCheckingP
+ _symbolic ______pSg 21ProximityReaderDaemon28EngagementCapabilityCheckingP
+ _symbolic _____y__________G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon17BrandDataResponseV 0bC4Core19EngagementErrorTypeO
+ _symbolic _____y__________G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon24BrandDataRefreshResponseV 0bC4Core19EngagementErrorTypeO
- _OBJC_CLASS_$_PKRemoteNetworkPaymentHandoffStageConfiguration
- __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore26EngagementServiceInterface_
- __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore34EngagementInternalServiceInterface_
- __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore26EngagementServiceInterface_
- __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore34EngagementInternalServiceInterface_
- __PROTOCOL__TtP19ProximityReaderCore26EngagementServiceInterface_
- __PROTOCOL__TtP19ProximityReaderCore34EngagementInternalServiceInterface_
- ___swift_closure_destructor.113Tm
- _symbolic ScCy_____y__________G_____G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon17BrandDataResponseV AC8APIErrorV s5NeverO
- _symbolic ScCy_____y__________G_____G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon24BrandDataRefreshResponseV AC8APIErrorV s5NeverO
- _symbolic _____y__________G s6ResultOsRi_zRi0_zrlE 21ProximityReaderDaemon24BrandDataRefreshResponseV AC8APIErrorV
CStrings:
+ "Brand request failed with error: %s"
+ "CorePeerPublisherDelegate: data session terminated, reason=%s"
+ "CorePeerSubscriberDelegate: subscriber failed to start: %s"
+ "Customer confirmed still-active; restarting inactivity timer"
+ "EngagementCustomerService - onDisconnect"
+ "EngagementCustomerService | not authorized"
+ "EngagementService - NFC unavailable"
+ "EngagementService - WiFi Aware not supported (device model)"
+ "Inactivity prompt expired - closing customer session"
+ "Received session terminated from merchant"
+ "init(_:_:_:_:_:_:_:registry:entitlementVerifier:logoProvider:nfcPayloadCodec:capabilityChecker:)"
+ "mockP2PInactivityTimeoutSeconds"
+ "startEngagementCustomerService(connection:)"
+ "wss://prs-originator-wpc-device.apple.com/"
- "CorePeerSubscriberDelegate: session terminated"
- "CorePeerSubscriberDelegate: subscriber failed"
- "ENGAGEMENT_REMOTE_PAYMENT_CONNECTED_DETAIL"
- "ENGAGEMENT_REMOTE_PAYMENT_CONNECTED_TITLE"
- "ENGAGEMENT_REMOTE_PAYMENT_REQUESTING_DETAIL"
- "ENGAGEMENT_REMOTE_PAYMENT_REQUESTING_TITLE"
- "ENGAGEMENT_REMOTE_PAYMENT_WAITING_DETAIL"
- "ENGAGEMENT_REMOTE_PAYMENT_WAITING_TITLE"
- "EngagementInternalService - onDisconnect"
- "EngagementInternalService | not authorized"
- "Prod sandbox profile installed, using prod sandbox environment"
- "init(_:_:_:_:_:_:_:registry:entitlementVerifier:logoProvider:nfcPayloadCodec:)"
- "startEngagementInternalService(connection:)"
- "wss://prs-originator"
```
