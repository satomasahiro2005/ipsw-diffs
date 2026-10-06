## ProximityReaderCore

> `/System/Library/PrivateFrameworks/ProximityReaderCore.framework/ProximityReaderCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13807c` | `0x139570` | **`+0x14f4`** |
| `__TEXT.__cstring` | `0x63ac` | `0x658c` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x35c6` | `0x36d6` | **`+0x110`** |
| `__DATA.__bss` | `0x3ba30` | `0x3bb20` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x12bb0` | `0x12c80` | **`+0xd0`** |
| `__TEXT.__const` | `0x1f478` | `0x1f518` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x6b40` | `0x6b80` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x6604` | `0x663a` | **`+0x36`** |
| `__TEXT.__swift5_reflstr` | `0x3a62` | `0x3a92` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x5f28` | `0x5f4c` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0x1110` | `0x1130` | **`+0x20`** |
| `__AUTH.__data` | `0x3398` | `0x33a8` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x4230` | `0x4240` | **`+0x10`** |
| `__DATA.__data` | `0x2fa0` | `0x2fb0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x673c` | `0x672c` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x8c8` | `0x8d8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1788` | `0x1780` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1c90` | `0x1c98` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x934` | `0x93c` | **`+0x8`** |

### Other Changes

```diff

-150.26.1.0.0
+150.28.1.0.0

-  Functions: 8844
-  Symbols:   3444
-  CStrings:  1087
+  Functions: 8856
+  Symbols:   3447
+  CStrings:  1105
Symbols:
+ __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore34EngagementCustomerServiceInterface_
+ __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore34EngagementMerchantServiceInterface_
+ __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore34EngagementCustomerServiceInterface_
+ __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore34EngagementMerchantServiceInterface_
+ __PROTOCOL__TtP19ProximityReaderCore34EngagementCustomerServiceInterface_
+ __PROTOCOL__TtP19ProximityReaderCore34EngagementMerchantServiceInterface_
+ ___swift_closure_destructor.48Tm
+ ___swift_closure_destructor.62Tm
+ ___swift_closure_destructor.81Tm
+ _associated conformance 19ProximityReaderCore37PublisherDataSessionTerminationReasonOSHAASQ
+ _flat unique 19ProximityReaderCore34EngagementCustomerServiceInterface_p
+ _symbolic $s19ProximityReaderCore34EngagementCustomerServiceInterfaceP
+ _symbolic $s19ProximityReaderCore34EngagementMerchantServiceInterfaceP
+ _symbolic _____ 19ProximityReaderCore37PublisherDataSessionTerminationReasonO
+ _symbolic ______p 19ProximityReaderCore34EngagementCustomerServiceInterfaceP
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 19ProximityReaderCore18SubscriberDelegate020_A6A26ECFAECED257FB5J11C40B856C5FALLC5StateO
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 19ProximityReaderCore18SubscriberDelegate020_A6A26ECFAECED257FB5H11C40B856C5FALLC5StateO So16os_unfair_lock_sV
- _OBJC_CLASS_$_WiFiAwareDeviceCapabilities
- __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore26EngagementServiceInterface_
- __PROTOCOL_INSTANCE_METHODS__TtP19ProximityReaderCore34EngagementInternalServiceInterface_
- __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore26EngagementServiceInterface_
- __PROTOCOL_METHOD_TYPES__TtP19ProximityReaderCore34EngagementInternalServiceInterface_
- __PROTOCOL__TtP19ProximityReaderCore26EngagementServiceInterface_
- __PROTOCOL__TtP19ProximityReaderCore34EngagementInternalServiceInterface_
- ___swift_closure_destructor.44Tm
- ___swift_closure_destructor.58Tm
- ___swift_closure_destructor.77Tm
- _flat unique 19ProximityReaderCore34EngagementInternalServiceInterface_p
- _symbolic $s19ProximityReaderCore26EngagementServiceInterfaceP
- _symbolic $s19ProximityReaderCore34EngagementInternalServiceInterfaceP
- _symbolic ______p 19ProximityReaderCore34EngagementInternalServiceInterfaceP
CStrings:
+ "MerchantKit-150.28.1"
+ "NFC Required Alert (engagement) was dismissed"
+ "NFC_DISABLED_ALERT_MESSAGE_ENGAGEMENT"
+ "Publisher data session terminated: reason=%s, datapathID=%hhu"
+ "Publisher pinCode was requested"
+ "RSSI performance data unavailable for %ld consecutive polls — stopping polling without firing signal lost"
+ "Subscriber is already connecting/connected, timeout is ignored"
+ "Subscriber's pid sent"
+ "inactivityTimeout"
+ "incompatibleRequest"
+ "internetSharingRequired"
+ "mockP2PInactivityTimeoutSeconds"
+ "pairVerifyAuthenticationFailure"
+ "pairedDeviceStoreUnavailable"
+ "pairingAlreadyPaired"
+ "pairingInvalidPassphrase"
+ "pairingInvalidPeerAttributes"
+ "pairingInvalidPin"
+ "pairingNoMetaData"
+ "pairingNoPeerSSI"
+ "showNFCDisabledDialogForEngagement(handler:)"
+ "• native %{private}s"
+ "• web %{private}s"
- "MerchantKit-150.26.1"
- "No WiFi Aware capabilities"
- "Publisher pinCode was requested: %{private}s"
- "Subscriber's pid sent)"
- "WiFi Aware %s supported"
```
