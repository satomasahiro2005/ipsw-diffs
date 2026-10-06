## PegasusConfiguration

> `/System/Library/PrivateFrameworks/PegasusConfiguration.framework/PegasusConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x470bc` | `0x46834` | **`-0x888`** |
| `__AUTH.__data` | `—` | `0x840` | **`+0x840`** |
| `__DATA_DIRTY.__data` | `0x1890` | `0x1050` | **`-0x840`** |
| `__AUTH.__objc_data` | `0x90` | `0x120` | **`+0x90`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x1a0` | **`-0x90`** |
| `__TEXT.__eh_frame` | `0x1cf0` | `0x1c90` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x3140` | `0x30f0` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0xf0f` | `0xedf` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x1342` | `0x1318` | **`-0x2a`** |
| `__DATA.__data` | `0xed0` | `0xea8` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `0x518` | `0x4f8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x14d8` | `0x14b8` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xdd0` | `0xdb8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d0` | `0x3e8` | **`+0x18`** |
| `__TEXT.__const` | `0x4f10` | `0x4f00` | **`-0x10`** |
| `__DATA_CONST.__const` | `0xa0` | `0x98` | **`-0x8`** |

### Other Changes

```diff

-3600.56.7.0.0
+3600.56.16.0.0

-  - /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices

+  - /System/Library/PrivateFrameworks/RegulatoryDomain.framework/RegulatoryDomain

+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 2030
-  Symbols:   877
-  CStrings:  353
+  Functions: 2009
+  Symbols:   872
+  CStrings:  352
Symbols:
+ _OBJC_CLASS_$_RDEstimate
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_PegasusConfiguration
- _OUTLINED_FUNCTION_113
- _OUTLINED_FUNCTION_114
- _get_type_metadata 15Synchronization5MutexVyScS12ContinuationVyyyYbc_GG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo34NSURLSessionTaskTransactionMetricsCSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic SSSgIego_
- _symbolic SSSgIegr_
- _symbolic _____ySsG s23_ContiguousArrayStorageC
CStrings:
+ "ConfigDebug: context.deviceCountryCode = %s"
+ "Request timeout has passed, exiting %s task"
- "ConfigDebug: context.geoDeviceCountryCode = %s"
- "Request timeout has passed, exiting additional tasks"
- "countryCodeProvider not set"
```
