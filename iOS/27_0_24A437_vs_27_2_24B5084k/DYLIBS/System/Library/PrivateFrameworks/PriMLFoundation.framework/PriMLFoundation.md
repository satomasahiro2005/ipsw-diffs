## PriMLFoundation

> `/System/Library/PrivateFrameworks/PriMLFoundation.framework/PriMLFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75834` | `0x77940` | **`+0x210c`** |
| `__AUTH_CONST.__auth_got` | `0xce0` | `0xe00` | **`+0x120`** |
| `__TEXT.__const` | `0x3ea8` | `0x3fb8` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x1ccd` | `0x1d9d` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x3a20` | `0x3ae0` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x28f8` | `0x2980` | **`+0x88`** |
| `__DATA.__bss` | `0x3590` | `0x3610` | **`+0x80`** |
| `__TEXT.__cstring` | `0x882` | `0x8f4` | **`+0x72`** |
| `__TEXT.__swift5_typeref` | `0xfde` | `0x104c` | **`+0x6e`** |
| `__DATA.__data` | `0x968` | `0x9c8` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x14b4` | `0x1510` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x19f0` | `0x1a48` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x11e1` | `0x1231` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x12d8` | `0x1318` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x27c` | `0x254` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x294` | `0x2a4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x12c` | `0x138` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x140` | `0x14c` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0xcc8` | `0xcd0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x248` | `0x24c` | **`+0x4`** |

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  Functions: 2025
-  Symbols:   698
-  CStrings:  199
+  Functions: 2059
+  Symbols:   722
+  CStrings:  209
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSObject
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ ___swift_closure_destructor.34Tm
+ ___swift_memcpy72_8
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _objc_autoreleaseReturnValue
+ _swift_retain_x2
+ _symbolic _____ 15PriMLFoundation17MorpheusTelemetryO
+ _symbolic _____ 15PriMLFoundation17MorpheusTelemetryO10ErrorTraceV
+ _symbolic _____Sg 15PriMLFoundation17MorpheusTelemetryO10ErrorTraceV
+ _symbolic _____Sg 8Morpheus12CrashCaptureC
+ _symbolic _____Sg 8Morpheus18TracebackCollectorC
+ _symbolic _____Sg s6MirrorV12DisplayStyleO
+ _symbolic _____Sg_ABt s6MirrorV12DisplayStyleO
+ _symbolic ______p s20TextOutputStreamableP
+ _symbolic ______p s23CustomStringConvertibleP
+ _symbolic ______p s28CustomDebugStringConvertibleP
+ _symbolic ______p______t s9CodingKeyP s13DecodingErrorO7ContextV
+ _symbolic ypXmT______t s13DecodingErrorO7ContextV
+ _type_layout_string 15PriMLFoundation17MorpheusTelemetryO10ErrorTraceV
- _swift_retain_x26
CStrings:
+ "Context: %s"
+ "Couldn't decode %s from recipe: %@"
+ "Data corrupted"
+ "Missing key '%s' in recipe"
+ "MorpheusUncleanTermination"
+ "Recipe for PFL/ETL task %s is missing `collectionIdPrefix`; falling back to plugin.useCase."
+ "Type mismatch for type '%s'"
+ "Unknown decoding error: %@"
+ "Value not found for type '%s'"
+ "com.apple.priml.Morpheus.ErrorTrace"
+ "taskParameters"
+ "transpilerVersion"
- "Recipe for PFL/ETL task %s is missing `collectionIdPrefix`; falling back to plugin[:useCase]."
- "task_parameters"
```
