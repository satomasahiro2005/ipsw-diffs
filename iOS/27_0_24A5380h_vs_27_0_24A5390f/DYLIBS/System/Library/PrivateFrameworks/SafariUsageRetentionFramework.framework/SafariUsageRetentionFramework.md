## SafariUsageRetentionFramework

> `/System/Library/PrivateFrameworks/SafariUsageRetentionFramework.framework/SafariUsageRetentionFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd48c` | `0x11cc0` | **`+0x4834`** |
| `__AUTH_CONST.__const` | `0x2e49` | `0x2909` | **`-0x540`** |
| `__TEXT.__cstring` | `0x5be` | `0x27e` | **`-0x340`** |
| `__TEXT.__const` | `0x964` | `0xc44` | **`+0x2e0`** |
| `__AUTH.__data` | `0x108` | `0x338` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x8d8` | `0xb08` | **`+0x230`** |
| `__TEXT.__swift5_fieldmd` | `0x240` | `0x3f8` | **`+0x1b8`** |
| `__TEXT.__constg_swiftt` | `0x240` | `0x3c0` | **`+0x180`** |
| `__TEXT.__swift5_typeref` | `0x325` | `0x44b` | **`+0x126`** |
| `__TEXT.__swift5_reflstr` | `0x142` | `0x252` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x3c8` | `0x4d0` | **`+0x108`** |
| `__DATA.__data` | `0x290` | `0x340` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x1d2` | `0x272` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x560` | `0x5e8` | **`+0x88`** |
| `__DATA.__bss` | `0x980` | `0xa00` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x7c` | `0xa0` | **`+0x24`** |
| `__TEXT.__swift5_types` | `0x34` | `0x54` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x34` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x28` | **`+0xc`** |

### Other Changes

```diff

-6.0.3.0.0
+6.0.6.0.0

+  - /System/Library/PrivateFrameworks/UnilogPlatformLibrary.framework/UnilogPlatformLibrary

+  - /System/Library/PrivateFrameworks/UnilogTelemetry.framework/UnilogTelemetry
+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 233
-  Symbols:   184
-  CStrings:  61
+  Functions: 298
+  Symbols:   212
+  CStrings:  38
Symbols:
+ _MGCopyAnswer
+ ___swift_memcpy320_8
+ ___swift_memcpy40_8
+ ___swift_memcpy80_8
+ _associated conformance 29SafariUsageRetentionFramework26AggregationIdentifierErrorOSHAASQ
+ _swift_deletedMethodError
+ _swift_release_x24
+ _symbolic $s29SafariUsageRetentionFramework17TelemetryReporterP
+ _symbolic $s29SafariUsageRetentionFramework19DeviceInfoProvidingP
+ _symbolic $s29SafariUsageRetentionFramework30AggregationIdentifierResolvingP
+ _symbolic Say_____G 29SafariUsageRetentionFramework0A8EventRowV
+ _symbolic Sb
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 19UnilogCommonLibrary14DevicePlatformO
+ _symbolic _____ 29SafariUsageRetentionFramework10DeviceInfoV
+ _symbolic _____ 29SafariUsageRetentionFramework20AggregationBatchSinkV
+ _symbolic _____ 29SafariUsageRetentionFramework21AggregationIdentifierV
+ _symbolic _____ 29SafariUsageRetentionFramework23UnilogTelemetryReporterV
+ _symbolic _____ 29SafariUsageRetentionFramework24SystemDeviceInfoProviderV
+ _symbolic _____ 29SafariUsageRetentionFramework26AggregationIdentifierErrorO
+ _symbolic _____ 29SafariUsageRetentionFramework35UnilogAggregationIdentifierProviderV
+ _symbolic _____ 29SafariUsageRetentionFramework6MapperV20ResolvedDeviceFields33_92F215989671849A2A924470E6C3713FLLV
+ _symbolic _____ 29SafariUsageRetentionFramework6MapperV5InputV
+ _symbolic _____Sg 19UnilogCommonLibrary14DevicePlatformO
+ _symbolic _____Sg 21UnilogPlatformLibrary14TelemetryErrorV
+ _symbolic _____Sg 21UnilogPlatformLibrary7VersionV
+ _symbolic _____Sg 29SafariUsageRetentionFramework21AggregationIdentifierV
+ _symbolic ______p 29SafariUsageRetentionFramework17TelemetryReporterP
+ _symbolic ______p 29SafariUsageRetentionFramework19DeviceInfoProvidingP
+ _symbolic ______p 29SafariUsageRetentionFramework30AggregationIdentifierResolvingP
+ _type_layout_string 29SafariUsageRetentionFramework13BookmarkStoreV
+ _type_layout_string 29SafariUsageRetentionFramework20AggregationBatchSinkV
+ _type_layout_string 29SafariUsageRetentionFramework6MapperV
- ___swift_memcpy200_8
- _associated conformance 29SafariUsageRetentionFramework20AggregationSinkErrorOSHAASQ
- _swift_release_x25
- _symbolic _____ 29SafariUsageRetentionFramework20AggregationSinkErrorO
- _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
CStrings:
+ "Donated %ld of %ld aggregates; %ld skipped for want of a valid identifier"
+ "Telemetry submit returned false"
+ "Telemetry submitNoWork returned false"
- "Mac Studio (2025)"
- "MacBook Air (13-inch, M3, 2024)"
- "MacBook Air (13-inch, M4, 2025)"
- "MacBook Air (13-inch, M5)"
- "MacBook Air (15-inch, M3, 2024)"
- "MacBook Air (15-inch, M4, 2025)"
- "MacBook Air (15-inch, M5)"
- "MacBook Pro (14-inch, M5 Max)"
- "MacBook Pro (14-inch, M5 Pro)"
- "MacBook Pro (14-inch, M5)"
- "MacBook Pro (14-inch, Nov 2024)"
- "MacBook Pro (16-inch, M5 Max)"
- "MacBook Pro (16-inch, M5 Pro)"
- "MacBook Pro (16-inch, Nov 2024)"
- "iMac (24-inch, 2024)"
- "iPad Air 11-inch"
- "iPad Air 11-inch (M3)"
- "iPad Air 11-inch (M4)"
- "iPad Air 13-inch"
- "iPad Air 13-inch (M3)"
- "iPad Pro 11-inch"
- "iPad Pro 11-inch (M5)"
- "iPad Pro 13-inch"
- "iPad Pro 13-inch (M5)"
- "iPhone 16 Pro Max"
- "iPhone 17 Pro Max"
```
