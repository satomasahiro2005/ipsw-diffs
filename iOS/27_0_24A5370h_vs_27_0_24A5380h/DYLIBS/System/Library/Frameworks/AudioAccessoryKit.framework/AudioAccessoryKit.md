## AudioAccessoryKit

> `/System/Library/Frameworks/AudioAccessoryKit.framework/AudioAccessoryKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x122a4` | `0x128a8` | **`+0x604`** |
| `__AUTH_CONST.__const` | `0xa90` | `0xb08` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x677` | `0x6a7` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1b8` | `0x1e8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4c8` | `0x4f8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x6c0` | `0x6e8` | **`+0x28`** |
| `__TEXT.__const` | `0xf10` | `0xf38` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x544` | `0x564` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x38f` | `0x3af` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x58a` | `0x5a4` | **`+0x1a`** |
| `__DATA.__data` | `0x390` | `0x378` | **`-0x18`** |
| `__DATA_CONST.__const` | `0xa8` | `0xb8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3ac` | `0x3b8` | **`+0xc`** |

### Other Changes

```diff

-40.31.1.0.0
+40.33.1.0.0

-  Functions: 446
-  Symbols:   371
-  CStrings:  77
+  Functions: 462
+  Symbols:   376
+  CStrings:  80
Symbols:
+ ___swift_closure_destructor.48Tm
+ _swift_endAccess
+ _swift_release_x1
+ _swift_retain_x1
+ _swift_retain_x23
+ _symbolic SbIegy_
+ _symbolic SbytIegnr_
+ _symbolic _____SgXw 17AudioAccessoryKit0aB12HeadTrackingC7SessionC
+ _symbolic ySbcSg
+ _xpc_dictionary_get_bool
- ___swift_closure_destructor.43Tm
- _get_type_metadata 15Synchronization5MutexVy17AudioAccessoryKit0cD16SensorDataWriterCSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDVScS12ContinuationVys6ResultOy17AudioAccessoryKit0H13SensorUpdatesV6UpdateOAM11StreamErrorOG_GGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _xpc_dictionary_set_bool
CStrings:
+ "Received head tracking state update: %{bool}d"
+ "headTrackingState"
+ "isActive"
```
