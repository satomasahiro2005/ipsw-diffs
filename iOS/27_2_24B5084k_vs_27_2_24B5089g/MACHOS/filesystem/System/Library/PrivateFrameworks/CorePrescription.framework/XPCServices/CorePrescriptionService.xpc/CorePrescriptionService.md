## CorePrescriptionService

> `/System/Library/PrivateFrameworks/CorePrescription.framework/XPCServices/CorePrescriptionService.xpc/CorePrescriptionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd5508` | `0xd3d0c` | **`-0x17fc`** |
| `__TEXT.__eh_frame` | `0xa930` | `0xa6c0` | **`-0x270`** |
| `__TEXT.__const` | `0xd20c` | `0xd3dc` | **`+0x1d0`** |
| `__TEXT.__objc_stubs` | `0x16a0` | `0x1760` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xdc2` | `0xe62` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x45b0` | `0x4528` | **`-0x88`** |
| `__DATA_CONST.__const` | `0x5318` | `0x52b8` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x5017` | `0x5067` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1864` | `0x181c` | **`-0x48`** |
| `__TEXT.__cstring` | `0x420c` | `0x41cc` | **`-0x40`** |
| `__DATA.__data` | `0x4520` | `0x44f0` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0xf10` | `0xf40` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x16c6` | `0x1698` | **`-0x2e`** |
| `__TEXT.__swift_as_cont` | `0xa30` | `0xa0c` | **`-0x24`** |
| `__TEXT.__swift5_reflstr` | `0x2263` | `0x2243` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x3ec` | `0x3d8` | **`-0x14`** |
| `__TEXT.__swift_as_ret` | `0x488` | `0x474` | **`-0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x938` | `0x928` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x2030` | `0x2040` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1020` | `0x1028` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-230.0.5.0.0
+230.40.1.0.0

-  Functions: 4319
-  Symbols:   524
-  CStrings:  1598
+  Functions: 4298
+  Symbols:   527
+  CStrings:  1596
Symbols:
+ _NSURLErrorDomain
+ _NSUnderlyingErrorKey
+ _objc_release_x9
CStrings:
+ "Factory calibration download exceeded its %{public}f maxDuration"
+ "Factory calibration download failed within its %{public}f sec maxDuration: %@"
+ "Recoverable error %@; retrying in %f sec; %f sec of maxDuration left"
+ "configuration"
+ "downloadCalibrationTimeout"
+ "get(_:configurator:)"
+ "setPreferAnonymousRequests:"
+ "setQualityOfService:"
+ "setTimeoutIntervalForRequest:"
+ "setTimeoutIntervalForResource:"
+ "timeout"
+ "userInfo"
- "Recoverable error %@; retrying in %f sec; %ld attempts remaining"
- "clientVersion"
- "cloudKitRetryCount"
- "items"
- "keyhash"
- "mapping"
- "message"
- "pubkeyEncItems"
- "recordId"
- "requestId"
- "results"
- "serialNumbers"
- "status"
- "timestamp"
```
