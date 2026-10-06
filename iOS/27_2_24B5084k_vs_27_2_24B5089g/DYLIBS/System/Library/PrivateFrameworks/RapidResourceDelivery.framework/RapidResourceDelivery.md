## RapidResourceDelivery

> `/System/Library/PrivateFrameworks/RapidResourceDelivery.framework/RapidResourceDelivery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77b28` | `0x7da28` | **`+0x5f00`** |
| `__DATA.__bss` | `0xa410` | `0xac10` | **`+0x800`** |
| `__TEXT.__const` | `0x6e68` | `0x72b8` | **`+0x450`** |
| `__AUTH_CONST.__const` | `0x3060` | `0x3218` | **`+0x1b8`** |
| `__TEXT.__eh_frame` | `0x3578` | `0x3718` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x18e0` | `0x1a20` | **`+0x140`** |
| `__TEXT.__swift5_fieldmd` | `0x1724` | `0x184c` | **`+0x128`** |
| `__AUTH.__data` | `0x510` | `0x628` | **`+0x118`** |
| `__DATA.__data` | `0x1288` | `0x1378` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x1478` | `0x1534` | **`+0xbc`** |
| `__TEXT.__swift5_typeref` | `0x1880` | `0x193a` | **`+0xba`** |
| `__TEXT.__swift5_reflstr` | `0xca0` | `0xd40` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xc09` | `0xc89` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xd60` | `0xdd0` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x1d48` | `0x1da8` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x5f4` | `0x634` | **`+0x40`** |
| `__DATA.__common` | `0xf8` | `0x110` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x1ec` | `0x200` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x330` | `0x338` | **`+0x8`** |

### Other Changes

```diff

-3605.2.1.0.0
+3605.3.1.0.0

+  - /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime

-  Functions: 1997
-  Symbols:   944
-  CStrings:  243
+  Functions: 2113
+  Symbols:   969
+  CStrings:  248
Symbols:
+ _TMGetKernelMonotonicClock
+ __swift_stdlib_strtod_clocale
+ _associated conformance 21RapidResourceDelivery12TimeSnapshotV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLOSHAASQ
+ _associated conformance 21RapidResourceDelivery12TimeSnapshotV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 21RapidResourceDelivery12TimeSnapshotV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 21RapidResourceDelivery18MonotonicTimeStateV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLOSHAASQ
+ _associated conformance 21RapidResourceDelivery18MonotonicTimeStateV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 21RapidResourceDelivery18MonotonicTimeStateV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _clock_gettime_nsec_np
+ _symbolic Say_____G s5UInt8V
+ _symbolic _____ 21RapidResourceDelivery11SystemClockO
+ _symbolic _____ 21RapidResourceDelivery12TimeSnapshotV
+ _symbolic _____ 21RapidResourceDelivery12TimeSnapshotV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLO
+ _symbolic _____ 21RapidResourceDelivery18MonotonicTimeStateV
+ _symbolic _____ 21RapidResourceDelivery18MonotonicTimeStateV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLO
+ _symbolic _____ s6UInt64V
+ _symbolic _____Sg 21RapidResourceDelivery12TimeSnapshotV
+ _symbolic _____Sg 21RapidResourceDelivery18MonotonicTimeStateV
+ _symbolic _____Sg s6UInt32V
+ _symbolic _____Sg_ABt 21RapidResourceDelivery12TimeSnapshotV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 21RapidResourceDelivery12TimeSnapshotV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 21RapidResourceDelivery18MonotonicTimeStateV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 21RapidResourceDelivery12TimeSnapshotV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 21RapidResourceDelivery18MonotonicTimeStateV10CodingKeys33_B2AD7C6D7ECAD0B79BB8CCDEE00454C4LLO
+ _sysctlbyname
CStrings:
+ "RRD clock manipulation detected: wall clock is %{public}fs behind trusted timebase"
+ "kern.bootsessionuuid"
+ "kern.monotonicclock_usecs"
+ "manifestFreshnessAnchor"
+ "updatesGraceAnchor"
```
