## UnilogTelemetry

> `/System/Library/PrivateFrameworks/UnilogTelemetry.framework/UnilogTelemetry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2409c` | `0x24700` | **`+0x664`** |
| `__AUTH_CONST.__const` | `0x858` | `0x968` | **`+0x110`** |
| `__DATA.__data` | `0x3a8` | `0x4b8` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x658` | `0x6cc` | **`+0x74`** |
| `__TEXT.__const` | `0xf54` | `0xfa4` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0xd40` | `0xd88` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x798` | `0x7d8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x5b4` | `0x5ec` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x8f8` | `0x928` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x6d3` | `0x6a3` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0xae1` | `0xb0b` | **`+0x2a`** |
| `__AUTH_CONST.__objc_const` | `0x478` | `0x4a0` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x2e8` | `0x2c8` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x54` | **`+0x8`** |

### Other Changes

```diff

-3600.13.1.0.0
+3600.14.2.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 864
-  Symbols:   488
+  Functions: 881
+  Symbols:   499
Symbols:
+ __IVARS__TtC15UnilogTelemetry19ThreadSafeLazyValue
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_instantiateGenericMetadata
+ ___unnamed_1
+ _bzero
+ _swift_allocateGenericClassMetadata
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_getGenericMetadata
+ _swift_initClassMetadata2
+ _symbolic _____ 15UnilogTelemetry19ThreadSafeLazyValueC
+ _symbolic _____ 15UnilogTelemetry19ThreadSafeLazyValueC3Box33_25340BDA73E13382301B576DA5DBEB1ALLV
+ _symbolic _____y__________XjSgG 15UnilogTelemetry19ThreadSafeLazyValueC l27IntelligencePlatformLibrary6Source_px6StreamRts_XPXGMq AD0I0O7StreamsO0A0O06HealthB0O
+ _symbolic _____y__________XjSgG 15UnilogTelemetry19ThreadSafeLazyValueC l27IntelligencePlatformLibrary6Source_px6StreamRts_XPXGMq AD0I0O7StreamsO0A0O23HealthAggregatedSummaryO
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 15UnilogTelemetry19ThreadSafeLazyValueC3Box33_25340BDA73E13382301B576DA5DBEB1ALLV
+ _symbolic xSg
- _free
- _swift_coroFrameAlloc
- _symbolic __________XjSgSg l27IntelligencePlatformLibrary6Source_px6StreamRts_XPXGMq AA0C0O7StreamsO6UnilogO15HealthTelemetryO
- _symbolic __________XjSgSg l27IntelligencePlatformLibrary6Source_px6StreamRts_XPXGMq AA0C0O7StreamsO6UnilogO23HealthAggregatedSummaryO
```
