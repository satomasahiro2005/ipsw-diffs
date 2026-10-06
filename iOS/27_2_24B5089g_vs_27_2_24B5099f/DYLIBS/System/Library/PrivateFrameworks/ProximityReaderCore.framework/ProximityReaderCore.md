## ProximityReaderCore

> `/System/Library/PrivateFrameworks/ProximityReaderCore.framework/ProximityReaderCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14aa60` | `0x14f41c` | **`+0x49bc`** |
| `__AUTH_CONST.__const` | `0x12ec0` | `0x13198` | **`+0x2d8`** |
| `__DATA.__bss` | `0x3be70` | `0x3c120` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0x3eb6` | `0x4066` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x6c70` | `0x6e14` | **`+0x1a4`** |
| `__TEXT.__const` | `0x1fa58` | `0x1fbf8` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x5ad0` | `0x5b80` | **`+0xb0`** |
| `__TEXT.__swift5_capture` | `0x9dc` | `0xa68` | **`+0x8c`** |
| `__DATA.__data` | `0x30e0` | `0x3160` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x6cf8` | `0x6d78` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x613c` | `0x61b4` | **`+0x78`** |
| `__TEXT.__cstring` | `0x677c` | `0x67dc` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x3c12` | `0x3c72` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x6914` | `0x6966` | **`+0x52`** |
| `__AUTH_CONST.__objc_const` | `0x4510` | `0x4550` | **`+0x40`** |
| `__AUTH.__data` | `0x3488` | `0x34b8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x17e0` | `0x1800` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x1cc0` | `0x1cd4` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x224` | `0x238` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x19c` | `0x1a8` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x158` | `0x164` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x1ae8` | `0x1af0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa88` | `0xa90` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1168` | `0x1170` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x948` | `0x950` | **`+0x8`** |

### Other Changes

```diff

-151.2.0.0.0
+151.5.0.0.0

-  Functions: 9038
-  Symbols:   3508
-  CStrings:  1149
+  Functions: 9118
+  Symbols:   3517
+  CStrings:  1161
Symbols:
+ ___swift_get_extra_inhabitant_index.108Tm
+ ___swift_get_extra_inhabitant_index.57Tm
+ ___swift_get_extra_inhabitant_index.66Tm
+ ___swift_get_extra_inhabitant_index.75Tm
+ ___swift_get_extra_inhabitant_index.99Tm
+ ___swift_store_extra_inhabitant_index.100Tm
+ ___swift_store_extra_inhabitant_index.109Tm
+ ___swift_store_extra_inhabitant_index.58Tm
+ ___swift_store_extra_inhabitant_index.67Tm
+ ___swift_store_extra_inhabitant_index.76Tm
+ _associated conformance 19ProximityReaderCore14WebMessageBodyV15PayloadEncodingOSHAASQ
+ _associated conformance 19ProximityReaderCore26MerchantActivityAttributesV12ContentStateV4StepO23CustomerEndedCodingKeys33_00D679C1C46288F88B15C3CF58BD4052LLOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 19ProximityReaderCore26MerchantActivityAttributesV12ContentStateV4StepO23CustomerEndedCodingKeys33_00D679C1C46288F88B15C3CF58BD4052LLOs0L3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 19ProximityReaderCore14WebMessageBodyV15PayloadEncodingO
+ _symbolic _____ 19ProximityReaderCore26MerchantActivityAttributesV12ContentStateV4StepO23CustomerEndedCodingKeys33_00D679C1C46288F88B15C3CF58BD4052LLO
+ _symbolic _____ s5UInt8V
+ _symbolic _____Iegy_ 19ProximityReaderCore38EngagementCustomerInitializationResultO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 19ProximityReaderCore26MerchantActivityAttributesV12ContentStateV4StepO23CustomerEndedCodingKeys33_00D679C1C46288F88B15C3CF58BD4052LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 19ProximityReaderCore26MerchantActivityAttributesV12ContentStateV4StepO23CustomerEndedCodingKeys33_00D679C1C46288F88B15C3CF58BD4052LLO
- ___swift_get_extra_inhabitant_index.102Tm
- ___swift_get_extra_inhabitant_index.51Tm
- ___swift_get_extra_inhabitant_index.60Tm
- ___swift_get_extra_inhabitant_index.69Tm
- ___swift_get_extra_inhabitant_index.93Tm
- ___swift_store_extra_inhabitant_index.103Tm
- ___swift_store_extra_inhabitant_index.52Tm
- ___swift_store_extra_inhabitant_index.61Tm
- ___swift_store_extra_inhabitant_index.70Tm
- ___swift_store_extra_inhabitant_index.94Tm
CStrings:
+ "Alert has no timed auto-dismiss; ending the finished live activity at once"
+ "Could not extend subscribe deadline for %hhu: %s"
+ "Dismissing live activity left by a previous session"
+ "Ending finished live activity"
+ "Finishing live activity"
+ "Invalid %s auth tag: %{private}s"
+ "Invalid %s iv: %{private}s"
+ "Invalid %s payload: %{private}s"
+ "Live activity is finishing; ignoring update"
+ "MerchantKit-151.5"
+ "No live activity to finish"
+ "Received new pairing session"
+ "Subscribe deadline extended to %lds for pairing with %hhu"
+ "checkoutComplete"
+ "connectPeer(payload:)"
+ "supportsBase64Payload"
- "Invalid hex auth tag: %{private}s"
- "Invalid hex iv: %{private}s"
- "Invalid hex payload: %{private}s"
- "MerchantKit-151.2"
```
