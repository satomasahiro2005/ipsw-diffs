## UnilogInstrumentation

> `/System/Library/PrivateFrameworks/UnilogInstrumentation.framework/UnilogInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18cc4` | `0x1a084` | **`+0x13c0`** |
| `__AUTH_CONST.__const` | `0x908` | `0x9a8` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xa70` | `0xaf8` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0xe4` | `0x140` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0x230` | `0x278` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x888` | `0x8c8` | **`+0x40`** |
| `__TEXT.__const` | `0x1010` | `0x1050` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x688` | `0x6b8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x2f1` | `0x311` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x5f8` | `0x60e` | **`+0x16`** |
| `__DATA.__data` | `0x640` | `0x650` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x34` | `0x44` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x50` | `0x58` | **`+0x8`** |

### Other Changes

```diff

-2.0.2.0.0
+2.0.3.0.0

+  - /System/Library/PrivateFrameworks/UnilogPlatformLibrary.framework/UnilogPlatformLibrary
+  - /System/Library/PrivateFrameworks/UnilogTelemetry.framework/UnilogTelemetry

-  Functions: 474
-  Symbols:   332
-  CStrings:  36
+  Functions: 486
+  Symbols:   334
+  CStrings:  37
Symbols:
+ _swift_retain_x28
+ _symbolic _____ 19UnilogCommonLibrary12StagingEventV0D12PayloadUnionO
+ _symbolic _____Sg 21UnilogPlatformLibrary14TelemetryErrorV
+ _symbolic _____Sg 21UnilogPlatformLibrary7VersionV
- ___swift_closure_destructor.29Tm
- _swift_retain_x26
CStrings:
+ "Telemetry not available"
```
