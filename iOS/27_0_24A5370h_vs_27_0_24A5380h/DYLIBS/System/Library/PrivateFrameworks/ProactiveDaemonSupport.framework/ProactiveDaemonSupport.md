## ProactiveDaemonSupport

> `/System/Library/PrivateFrameworks/ProactiveDaemonSupport.framework/ProactiveDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2340c` | `0x21a78` | **`-0x1994`** |
| `__AUTH.__data` | `0x1d8` | `0x78` | **`-0x160`** |
| `__TEXT.__oslogstring` | `0xb7d` | `0xa9d` | **`-0xe0`** |
| `__DATA_DIRTY.__data` | `0x6d0` | `0x790` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x730` | `0x680` | **`-0xb0`** |
| `__DATA.__bss` | `0x1380` | `0x1400` | **`+0x80`** |
| `__DATA.__data` | `0x838` | `0x7b8` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x80` | `—` | **`-0x80`** |
| `__TEXT.__const` | `0x1910` | `0x1890` | **`-0x80`** |
| `__AUTH_CONST.__auth_got` | `0xa98` | `0xa38` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x1e20` | `0x1dd0` | **`-0x50`** |
| `__TEXT.__cstring` | `0x4d7` | `0x487` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0xd6e` | `0xd1e` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xbc8` | `0xb78` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0xe80` | `0xe38` | **`-0x48`** |
| `__TEXT.__eh_frame` | `0x12f0` | `0x12a8` | **`-0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x750` | `0x71c` | **`-0x34`** |
| `__TEXT.__swift5_capture` | `0x4e0` | `0x4cc` | **`-0x14`** |
| `__DATA.__common` | `0x18` | `0x8` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x444` | `0x434` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x20` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0xbc` | `0xb8` | **`-0x4`** |

### Other Changes

```diff

-3600.144.5.501.3
+3600.147.12.501.3

-  - /System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics

-  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 1188
-  Symbols:   225
-  CStrings:  75
+  Functions: 1161
+  Symbols:   222
+  CStrings:  70
Symbols:
+ __pds_os_variant_has_internal_diagnostics
+ _os_variant_has_internal_diagnostics
- _WriteCrashReportWithStackshot
- _getpid
- _swift_getSingletonMetadata
- _swift_runtimeSupportsNoncopyableTypes
- _swift_updateClassMetadata2
CStrings:
- "WATCHDOG EXPIRED: Stackshot acquired"
- "WATCHDOG EXPIRED: The watchdog for %{public}s has expired. Capturing stackshot."
- "WATCHDOG EXPIRED: The watchdog for %{public}s has expired. Unable to get stackshot."
- "Watchdog expired"
- "com.apple.proactivedaemonsupport.watchdog"
```
