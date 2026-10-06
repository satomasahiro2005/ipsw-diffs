## ReportCrashService

> `/System/Library/Frameworks/OSAnalytics.framework/XPCServices/ReportCrashService.xpc/ReportCrashService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f7ec` | `0x4fa20` | **`+0x234`** |
| `__TEXT.__oslogstring` | `0x325e` | `0x330e` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x44ef` | `0x4563` | **`+0x74`** |
| `__TEXT.__swift5_reflstr` | `0x493` | `0x4ef` | **`+0x5c`** |
| `__DATA.__objc_const` | `0x2b08` | `0x2b60` | **`+0x58`** |
| `__TEXT.__cstring` | `0x5985` | `0x59d5` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x7a40` | `0x7a80` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3d00` | `0x3d40` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `0x540` | `0x570` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x6a8` | `0x6d8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x68e` | `0x666` | **`-0x28`** |
| `__DATA.__data` | `0xbd8` | `0xbc0` | **`-0x18`** |
| `__TEXT.__const` | `0xdf8` | `0xde0` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x26e0` | `0x26d0` | **`-0x10`** |
| `__DATA.__common` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x10e0` | `0x10e8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1380` | `0x1378` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x16b8` | `0x16c0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xfa4` | `0xfac` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xbd8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1049.0.0.502.1
+1056.0.3.0.0

-  Functions: 1023
+  Functions: 1027

-  CStrings:  2274
+  CStrings:  2284
Symbols:
+ _AnalyticsSendEvent
+ _rcs_has_active_extension
- _swift_initStaticObject
- _swift_retain_x27
CStrings:
+ "CPUTrace enabled on ReportCrash"
+ "CPUTraceEnabled not set; skipping tailspin save"
+ "[RCS_DIRTY_EXIT] reason=0 hasActiveExtension=%d"
+ "[RCS_DIRTY_EXIT] reason=1 hasActiveExtension=%d"
+ "_inFlightLock"
+ "_isExtensionInFlight"
+ "com.apple.ReportCrashService.dirtyExit"
+ "hasActiveExtension"
+ "isEligibleForSharingWithThirdPartyDevelopers"
+ "notifIsGameTestModeUnsupported"
```
