## PegasusKit

> `/System/Library/PrivateFrameworks/PegasusKit.framework/PegasusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeb23c` | `0xee554` | **`+0x3318`** |
| `__TEXT.__eh_frame` | `0x626c` | `0x6604` | **`+0x398`** |
| `__AUTH.__data` | `0x178` | `0x478` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x2c5f` | `0x2d8f` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x2bd0` | `0x2cc0` | **`+0xf0`** |
| `__TEXT.__const` | `0x6110` | `0x61e0` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x2b91` | `0x2c41` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x2530` | `0x25c0` | **`+0x90`** |
| `__DATA.__data` | `0xca0` | `0xd30` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x2c58` | `0x2ce4` | **`+0x8c`** |
| `__AUTH.__objc_data` | `0x120` | `0x170` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x2dac` | `0x2dfa` | **`+0x4e`** |
| `__TEXT.__swift5_fieldmd` | `0x1d20` | `0x1d64` | **`+0x44`** |
| `__AUTH_CONST.__const` | `0xb8a0` | `0xb8d8` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1b08` | `0x1b38` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x484` | `0x4b4` | **`+0x30`** |
| `__DATA.__common` | `0x60` | `0x88` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x2313` | `0x2327` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x264` | `0x278` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x208` | `0x218` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x260` | `0x264` | **`+0x4`** |

### Other Changes

```diff

-3600.56.16.0.0
+3600.56.21.0.0

-  Functions: 5377
-  Symbols:   1535
-  CStrings:  530
+  Functions: 5456
+  Symbols:   1545
+  CStrings:  542
Symbols:
+ __DATA__TtC10PegasusKit41CreatorAgentKitProxyForDeviceExpertSearch
+ __IVARS__TtC10PegasusKit41CreatorAgentKitProxyForDeviceExpertSearch
+ __METACLASS_DATA__TtC10PegasusKit41CreatorAgentKitProxyForDeviceExpertSearch
+ _symbolic _____ 10PegasusKit012CreatorAgentB26ProxyForDeviceExpertSearchC
+ _symbolic _____ 10PegasusKit9OSVariantV
+ _symbolic ______SSt 10PegasusAPI020Apple_Parsec_Search_A12QueryContextV
+ _symbolic _____y_____G 16GRPCCoreInternal13ClientRequestV 10PegasusAPI034Apple_Parsec_DeviceExpert_V1alpha_ij6SearchD0V
+ _symbolic _____y_____G 16GRPCCoreInternal14ClientResponseV 10PegasusAPI034Apple_Parsec_DeviceExpert_V1alpha_ij6SearchD0V
+ _symbolic _____y_____G 20GRPCProtobufInternal18ProtobufSerializerV 10PegasusAPI034Apple_Parsec_DeviceExpert_V1alpha_iJ13SearchRequestV
+ _symbolic _____y_____G 20GRPCProtobufInternal20ProtobufDeserializerV 10PegasusAPI034Apple_Parsec_DeviceExpert_V1alpha_iJ14SearchResponseV
CStrings:
+ ".PARPrivateAccessTokenIssuer"
+ "CreatorAgentDE"
+ "CreatorAgentDE feature flag is disabled"
+ "Failed to decode DeviceExpertSearchRequest: %s"
+ "Failed to encode DeviceExpertSearchResponse to JSON: %s"
+ "context+PAT fetch failed: %s"
+ "creator-studio-de.issuer.apple.com"
+ "proxyForCreatorAgentKitDeviceExpertSearch"
+ "search call succeeded"
+ "search got non ok status"
+ "started processing search request"
+ "v1/deviceexpert/search"
```
