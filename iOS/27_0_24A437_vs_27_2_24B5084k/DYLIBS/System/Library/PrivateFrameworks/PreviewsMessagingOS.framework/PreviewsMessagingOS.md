## PreviewsMessagingOS

> `/System/Library/PrivateFrameworks/PreviewsMessagingOS.framework/PreviewsMessagingOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc130` | `0xbcfc8` | **`+0xe98`** |
| `__TEXT.__cstring` | `0x38a2` | `0x39ef` | **`+0x14d`** |
| `__TEXT.__swift5_reflstr` | `0x263b` | `0x26d0` | **`+0x95`** |
| `__AUTH_CONST.__const` | `0x10391` | `0x10409` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0x5150` | `0x51a8` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x4610` | `0x464c` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x4158` | `0x4130` | **`-0x28`** |
| `__TEXT.__const` | `0x12c40` | `0x12c58` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x3605` | `0x3611` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xe88` | `0xe90` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x1cf` | `0x1c7` | **`-0x8`** |

### Other Changes

```diff

-24.0.45.1.0
+24.20.6.0.0

-  Functions: 6271
-  Symbols:   1684
-  CStrings:  537
+  Functions: 6283
+  Symbols:   1683
+  CStrings:  540
Symbols:
+ ___swift_closure_destructor.12Tm
+ ___swift_closure_destructor.15Tm
+ ___swift_closure_destructor.5Tm
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyV0a10FoundationC025PropertyListRepresentableAA0gH5ValueAdEP_AD0gH4Type
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyVSHAASQ
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyVs26ExpressibleByStringLiteralAA0hI4TypesADP_s01_fg7BuiltinhI0
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyVs26ExpressibleByStringLiteralAAs0fg23ExtendedGraphemeClusterI0
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyVs33ExpressibleByUnicodeScalarLiteralAA0hiJ4TypesADP_s01_fg7BuiltinhiJ0
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyVs43ExpressibleByExtendedGraphemeClusterLiteralAA0hijK4TypesADP_s01_fg7BuiltinhijK0
+ _associated conformance 19PreviewsMessagingOS17ArchivingStrategyVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0fg13UnicodeScalarK0
+ _associated conformance 19PreviewsMessagingOS24ArchivingStrategyPayloadV0a10FoundationC025PropertyListRepresentableAA0hI5ValueAdEP_AD0hI4Type
+ _associated conformance 19PreviewsMessagingOS24ArchivingStrategyPayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLOSHAASQ
+ _associated conformance 19PreviewsMessagingOS31RequestArchivingStrategyPayloadV0a10FoundationC025PropertyListRepresentableAA0iJ5ValueAdEP_AD0iJ4Type
+ _associated conformance 19PreviewsMessagingOS31RequestArchivingStrategyPayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLOSHAASQ
+ _symbolic Say_____G 19PreviewsMessagingOS17ArchivingStrategyV
+ _symbolic _____ 19PreviewsMessagingOS17ArchivingStrategyV
+ _symbolic _____ 19PreviewsMessagingOS24ArchivingStrategyPayloadV
+ _symbolic _____ 19PreviewsMessagingOS24ArchivingStrategyPayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLO
+ _symbolic _____ 19PreviewsMessagingOS31RequestArchivingStrategyPayloadV
+ _symbolic _____ 19PreviewsMessagingOS31RequestArchivingStrategyPayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 19PreviewsMessagingOS17ArchivingStrategyV
+ _type_layout_string 19PreviewsMessagingOS24ArchivingStrategyPayloadV
+ _type_layout_string 19PreviewsMessagingOS31RequestArchivingStrategyPayloadV
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.2Tm
- ___swift_closure_destructor.36Tm
- ___swift_closure_destructor.4Tm
- _associated conformance 19PreviewsMessagingOS15ContentOverrideV0a10FoundationC025PropertyListRepresentableAA0gH5ValueAdEP_AD0gH4Type
- _associated conformance 19PreviewsMessagingOS15ContentOverrideVSHAASQ
- _associated conformance 19PreviewsMessagingOS15ContentOverrideVs26ExpressibleByStringLiteralAA0hI4TypesADP_s01_fg7BuiltinhI0
- _associated conformance 19PreviewsMessagingOS15ContentOverrideVs26ExpressibleByStringLiteralAAs0fg23ExtendedGraphemeClusterI0
- _associated conformance 19PreviewsMessagingOS15ContentOverrideVs33ExpressibleByUnicodeScalarLiteralAA0hiJ4TypesADP_s01_fg7BuiltinhiJ0
- _associated conformance 19PreviewsMessagingOS15ContentOverrideVs43ExpressibleByExtendedGraphemeClusterLiteralAA0hijK4TypesADP_s01_fg7BuiltinhijK0
- _associated conformance 19PreviewsMessagingOS15ContentOverrideVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0fg13UnicodeScalarK0
- _associated conformance 19PreviewsMessagingOS22ContentOverridePayloadV0a10FoundationC025PropertyListRepresentableAA0hI5ValueAdEP_AD0hI4Type
- _associated conformance 19PreviewsMessagingOS22ContentOverridePayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLOSHAASQ
- _associated conformance 19PreviewsMessagingOS29RequestContentOverridePayloadV0a10FoundationC025PropertyListRepresentableAA0iJ5ValueAdEP_AD0iJ4Type
- _associated conformance 19PreviewsMessagingOS29RequestContentOverridePayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLOSHAASQ
- _symbolic Say_____G 19PreviewsMessagingOS15ContentOverrideV
- _symbolic _____ 19PreviewsMessagingOS15ContentOverrideV
- _symbolic _____ 19PreviewsMessagingOS22ContentOverridePayloadV
- _symbolic _____ 19PreviewsMessagingOS22ContentOverridePayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLO
- _symbolic _____ 19PreviewsMessagingOS29RequestContentOverridePayloadV
- _symbolic _____ 19PreviewsMessagingOS29RequestContentOverridePayloadV3Key33_293DDC6361BDCDF53D47321043E2DDD1LLO
- _symbolic _____Sg 19PreviewsMessagingOS15ContentOverrideV
- _type_layout_string 19PreviewsMessagingOS22ContentOverridePayloadV
- _type_layout_string 19PreviewsMessagingOS29RequestContentOverridePayloadV
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/Daemon Interface/DaemonConnection.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/Daemon Interface/PreviewServiceInterface.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/AsyncMessageStream.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/Components/Bridge.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/Components/Fork.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/Components/Junction.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/Components/Outlet.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/Components/PipeEvent.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/Concrete Systems/SampleStreamAgent.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/MessagePipe.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe/MessageStream.swift"
+ "Ultraviolet.DefaultArchivingStrategy"
+ "archivingStrategy"
+ "requestedStrategies"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/AsyncMessageStream.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/Bridge.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/DaemonConnection.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/Fork.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/Junction.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessagePipe.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/MessageStream.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/Outlet.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/PipeEvent.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/PreviewServiceInterface.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsMessaging/Sources/PreviewsMessaging/SampleStreamAgent.swift"
```
