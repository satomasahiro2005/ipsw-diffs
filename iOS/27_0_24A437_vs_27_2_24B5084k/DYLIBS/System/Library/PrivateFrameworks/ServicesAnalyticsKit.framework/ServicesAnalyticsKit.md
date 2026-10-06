## ServicesAnalyticsKit

> `/System/Library/PrivateFrameworks/ServicesAnalyticsKit.framework/ServicesAnalyticsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a44` | `0x12860` | **`+0xe1c`** |
| `__TEXT.__eh_frame` | `0x750` | `0x900` | **`+0x1b0`** |
| `__DATA.__bss` | `0xa80` | `0xb80` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x760` | `0x6d0` | **`-0x90`** |
| `__TEXT.__cstring` | `0x24b` | `0x2d6` | **`+0x8b`** |
| `__TEXT.__unwind_info` | `0x4e0` | `0x558` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x4ec` | `0x492` | **`-0x5a`** |
| `__TEXT.__swift5_reflstr` | `0x284` | `0x234` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x2b0` | `0x27c` | **`-0x34`** |
| `__TEXT.__swift_as_cont` | `0x24` | `0x58` | **`+0x34`** |
| `__AUTH_CONST.__auth_got` | `0x6e8` | `0x708` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x294` | `0x278` | **`-0x1c`** |
| `__DATA.__data` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xa4` | `0xac` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x38` | `0x34` | **`-0x4`** |

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

-  Functions: 385
-  Symbols:   257
-  CStrings:  23
+  Functions: 400
+  Symbols:   261
+  CStrings:  27
Symbols:
+ ___swift_assignWithCopy_strong
+ ___swift_assignWithTake_strong
+ ___swift_destroy_strong
+ ___swift_initWithCopy_strong
+ _objc_release_x25
+ _objc_retain_x19
+ _objc_retain_x24
+ _swift_getErrorValue
+ _symbolic _____Sg 21ServicesAnalyticsCore0C30OriginProcessAMSMetricsContextV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 21ServicesAnalyticsCore0F12MetricsEventV
- ___swift_memcpy0_1
- ___swift_memcpy9_8
- _objc_release_x21
- _symbolic _____ 20ServicesAnalyticsKit7MetricsV15ValidationErrorO
- _symbolic _____9mediaType_Sb25personalizeNetworkRequestt 21ServicesAnalyticsCore0C16AccountMediaTypeO
- _symbolic _____Sg9mediaType_Sb25personalizeNetworkRequestt 20ServicesAnalyticsKit16AccountMediaTypeO
CStrings:
+ "(internalActor: "
+ ".internalError(underlyingError: "
+ ".xpcDecodingError(underlyingError: "
+ ".xpcEncodingError(underlyingError: "
+ ".xpcError(underlyingError: "
- "associateWithActiveMediaAccountOnEnqueue(mediaType: "
```
