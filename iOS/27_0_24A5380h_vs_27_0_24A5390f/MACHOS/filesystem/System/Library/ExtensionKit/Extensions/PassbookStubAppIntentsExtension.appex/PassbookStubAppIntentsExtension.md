## PassbookStubAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/PassbookStubAppIntentsExtension.appex/PassbookStubAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fdc` | `0x4a4c` | **`+0xa70`** |
| `__DATA.__bss` | `0xd00` | `0x1000` | **`+0x300`** |
| `__TEXT.__const` | `0x820` | `0x9c8` | **`+0x1a8`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x710` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x33a` | `0x3ae` | **`+0x74`** |
| `__DATA_CONST.__auth_got` | `0x320` | `0x390` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xc0` | `0x128` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0x3b0` | `0x410` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xe0` | `0x140` | **`+0x60`** |
| `__DATA.__data` | `0x1a0` | `0x1e8` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0xea` | `0x129` | **`+0x3f`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x228` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0xd8` | `0x108` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x359` | `0x381` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xf8` | `0x118` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1d3` | `0x1f3` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xe8` | `0x104` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x38` | `0x50` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x68` | `0x80` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1686.3.0.0.0
+1689.3.0.0.0

-  Functions: 138
-  Symbols:   95
-  CStrings:  24
+  Functions: 157
+  Symbols:   117
+  CStrings:  27
Symbols:
+ _OBJC_CLASS_$_PKAnalyticsReporter
+ _PKAnalyticsReportErrorTypeHandoffBiometricsLockedOut
+ _PKAnalyticsReportErrorTypeHandoffFeatureNotSupported
+ _PKAnalyticsReportErrorTypeHandoffNoCompatibleCards
+ _PKAnalyticsReportErrorTypeHandoffUnknownFailure
+ _PKAnalyticsReportErrorTypeHandoffUnsupportedVersion
+ _PKAnalyticsReportErrorTypeKey
+ _PKAnalyticsReportEventKey
+ _PKAnalyticsReportEventTypeHandoffNotTriggered
+ _PKAnalyticsReportPageTagKey
+ _PKAnalyticsReportProductModelKey
+ _PKAnalyticsReportRemoteNetworkPaymentLoadingTag
+ _PKAnalyticsSubjectInApp
+ _PKProductType
+ _objc_release_x28
+ _objc_retain_x24
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x27
+ _objc_retain_x28
+ _objc_retain_x9
+ _swift_initStackObject
CStrings:
+ "beginSubjectReporting:"
+ "endSubjectReporting:"
+ "subject:sendEvent:"
```
