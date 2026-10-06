## CoreODIEssentials

> `/System/Library/PrivateFrameworks/CoreODIEssentials.framework/CoreODIEssentials`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc2e8` | `0x2018bc` | **`+0x55d4`** |
| `__TEXT.__eh_frame` | `0x14c58` | `0x15070` | **`+0x418`** |
| `__DATA.__bss` | `0x17190` | `0x17510` | **`+0x380`** |
| `__TEXT.__const` | `0x270d0` | `0x27430` | **`+0x360`** |
| `__AUTH_CONST.__objc_const` | `0x5910` | `0x5ae0` | **`+0x1d0`** |
| `__TEXT.__unwind_info` | `0x7d50` | `0x7ed0` | **`+0x180`** |
| `__AUTH.__data` | `0x720` | `0x880` | **`+0x160`** |
| `__AUTH_CONST.__const` | `0x10c90` | `0x10d90` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0xb633` | `0xb723` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x4ba7` | `0x4c89` | **`+0xe2`** |
| `__TEXT.__cstring` | `0x12c2f` | `0x12d0f` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x5c9c` | `0x5d54` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x8f78` | `0x9024` | **`+0xac`** |
| `__TEXT.__swift_as_cont` | `0x14f8` | `0x1574` | **`+0x7c`** |
| `__DATA.__data` | `0x2278` | `0x22e8` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x6458` | `0x64c8` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x6a0` | `0x6d0` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x8a4` | `0x8cc` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x688` | `0x6ac` | **`+0x24`** |
| `__DATA_CONST.__got` | `0xb80` | `0xba0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x16b8` | `0x16d8` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x1004` | `0x1024` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x190` | `0x1a4` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x66c` | `0x678` | **`+0xc`** |
| `__DATA.__common` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc38` | `0xc40` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x888` | `0x880` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0xb8` | `0xbc` | **`+0x4`** |

### Other Changes

```diff

-27.0.61.0.0
+27.2.2.0.0

+  - /System/Library/PrivateFrameworks/SystemStatus.framework/SystemStatus

-  Functions: 8590
-  Symbols:   2996
-  CStrings:  1557
+  Functions: 8680
+  Symbols:   3023
+  CStrings:  1564
Symbols:
+ _OBJC_CLASS_$_STBackgroundActivitiesStatusDomain
+ _STBackgroundActivityIdentifierFullScreenWebRTCCapture
+ _STBackgroundActivityIdentifierScreenReplayRecording
+ _STBackgroundActivityIdentifierScreenSharing
+ _STBackgroundActivityIdentifierScreenSharingServer
+ _STBackgroundActivityIdentifierSharePlayScreenSharing
+ _STBackgroundActivityIdentifierWebRTCCapture
+ __DATA__TtC17CoreODIEssentials19ScreenCaptureStatus
+ __DATA__TtC17CoreODIEssentials22TelemetrySpanCollector
+ __IVARS__TtC17CoreODIEssentials19ScreenCaptureStatus
+ __IVARS__TtC17CoreODIEssentials22TelemetrySpanCollector
+ __METACLASS_DATA__TtC17CoreODIEssentials19ScreenCaptureStatus
+ __METACLASS_DATA__TtC17CoreODIEssentials22TelemetrySpanCollector
+ ___swift_closure_destructor.123Tm
+ ___swift_closure_destructor.129Tm
+ ___swift_closure_destructor.234Tm
+ ___swift_closure_destructor.238Tm
+ ___swift_closure_destructor.254Tm
+ ___swift_closure_destructor.290Tm
+ ___swift_closure_destructor.77Tm
+ _associated conformance So30STBackgroundActivityIdentifieraSHSCSQ
+ _associated conformance So30STBackgroundActivityIdentifieras20_SwiftNewtypeWrapperSCSY
+ _associated conformance So30STBackgroundActivityIdentifieras20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic $s17CoreODIEssentials28ScreenCaptureStatusProvidingP
+ _symbolic So34STBackgroundActivitiesStatusDomainC
+ _symbolic _____ 17CoreODIEssentials19ScreenCaptureStatusC
+ _symbolic _____ 17CoreODIEssentials22TelemetrySpanCollectorC
+ _symbolic _____ So30STBackgroundActivityIdentifiera
+ _symbolic _____IeAgHr_ 17CoreODIEssentials24RealTimeTelemetryManagerC
+ _symbolic ______p 17CoreODIEssentials28ScreenCaptureStatusProvidingP
+ _symbolic _____ySay_____GG 2os21OSAllocatedUnfairLockV 17CoreODIEssentials20TelemetryDataRequestV4SpanV
+ _symbolic _____ySay_____G_____G s13ManagedBufferCsRi__rlE 17CoreODIEssentials20TelemetryDataRequestV4SpanV So16os_unfair_lock_sV
+ _symbolic _____y_____G s11_SetStorageC So30STBackgroundActivityIdentifiera
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 17CoreODIEssentials20TelemetryDataRequestV4SpanV
- ___swift_closure_destructor.124Tm
- ___swift_closure_destructor.130Tm
- ___swift_closure_destructor.233Tm
- ___swift_closure_destructor.237Tm
- ___swift_closure_destructor.253Tm
- ___swift_closure_destructor.289Tm
- ___swift_closure_destructor.78Tm
CStrings:
+ "CoreODIEssentials/ScreenCaptureStatus.swift"
+ "Failed to get screen capture status after "
+ "InnerODISession"
+ "Network request for TrustInsights session"
+ "Skipping sending real-time telemetry as it's disabled"
+ "bodyBase64EncodedCBOR"
+ "c31d6db4"
+ "isSharingScreenOnCall"
- "Skipping real-time telemetry init as it's disabled"
```
