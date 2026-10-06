## SearchAnalyticsWorker

> `/System/Library/ExtensionKit/Extensions/SearchAnalyticsWorker.appex/SearchAnalyticsWorker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40ec` | `0x372c` | **`-0x9c0`** |
| `__DATA_CONST.__auth_ptr` | `0xb0` | `0x1b0` | **`+0x100`** |
| `__DATA.__objc_const` | `0xd8` | `—` | **`-0xd8`** |
| `__TEXT.__const` | `0x210` | `0x2e2` | **`+0xd2`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x590` | **`-0xa0`** |
| `__DATA_CONST.__got` | `0x70` | `0x100` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x21` | `0xa3` | **`+0x82`** |
| `__DATA.__bss` | `0x100` | `0x180` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x138` | `0xc0` | **`-0x78`** |
| `__DATA.__data` | `0x138` | `0xc8` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x7c` | `0x28` | **`-0x54`** |
| `__DATA_CONST.__auth_got` | `0x320` | `0x2d0` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0xd6` | `0x11e` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x168` | `0x128` | **`-0x40`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x58` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x3c` | `—` | **`-0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x38` | `0x10` | **`-0x28`** |
| `__TEXT.__objc_classname` | `0x24` | `—` | **`-0x24`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x50` | **`+0x24`** |
| `__TEXT.__cstring` | `0x44` | `0x64` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x47` | `0x34` | **`-0x13`** |
| `__TEXT.__eh_frame` | `0x3a0` | `0x390` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x2c` | `0x3c` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x28` | `0x20` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x8` | `0xc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x8` | `0x4` | **`-0x4`** |
| `__TEXT.__objc_methtype` | `0x1` | `—` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.56.26.11.2
+3605.21.1.1.1

+  - /System/Library/PrivateFrameworks/PoirotAnalytics.framework/PoirotAnalytics

+  - /System/Library/PrivateFrameworks/PoirotSchematizer.framework/PoirotSchematizer

-  Functions: 108
-  Symbols:   89
-  CStrings:  18
+  Functions: 113
+  Symbols:   64
+  CStrings:  12
Symbols:
+ _objc_release_x24
+ _swift_allocError
+ _swift_willThrow
- _OBJC_CLASS_$__TtCs12_SwiftObject
- _OBJC_METACLASS_$__TtCs12_SwiftObject
- __objc_empty_cache
- __swift_stdlib_bridgeErrorToNSError
- _objc_release_x23
- _objc_release_x26
- _objc_release_x8
- _objc_retain_x21
- _objc_retain_x8
- _swift_beginAccess
- _swift_deallocClassInstance
- _swift_deallocObject
- _swift_deletedMethodError
- _swift_dynamicCast
- _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_release_x19
- _swift_release_x23
- _swift_release_x24
- _swift_release_x25
- _swift_release_x27
- _swift_release_x28
- _swift_release_x8
- _swift_retain_x19
- _swift_retain_x23
- _swift_retain_x24
- _swift_retain_x25
- _swift_retain_x26
- _swift_retain_x27
CStrings:
+ "Failed to subscribe to known recipes: %s"
+ "SAW mainDatabaseConfig: FAILED to load feedback manifest: %s"
+ "SAW mainDatabaseConfig: loaded manifest with %ld messages, %ld enums"
+ "com.apple.poirot"
- "Config found. Task params: %s"
- "No valid config found"
- "On-demand task completed %ld iteration(s): %@"
- "On-demand task is finished: %@"
- "On-demand task is interrupted: %@"
- "On-demand task started: %@"
- "Unexpected error: %@"
- "_TtC21SearchAnalyticsWorker7SAWTask"
- "context"
- "identifier"
```
