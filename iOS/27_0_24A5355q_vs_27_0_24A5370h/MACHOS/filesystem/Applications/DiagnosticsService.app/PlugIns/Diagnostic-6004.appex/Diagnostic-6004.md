## Diagnostic-6004

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6004.appex/Diagnostic-6004`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1426c` | `0x14674` | **`+0x408`** |
| `__DATA.__objc_const` | `0xcf0` | `0xe10` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x1248` | `0x1368` | **`+0x120`** |
| `__TEXT.__auth_stubs` | `0xe90` | `0xf50` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0xd20` | `0xdc0` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x750` | `0x7b0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x4e4` | `0x544` | **`+0x60`** |
| `__DATA.__objc_data` | `0x7a8` | `0x7f8` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x4bb` | `0x50b` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x4c8` | `0x500` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xc10` | `0xc38` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x4a8` | `0x4c0` | **`+0x18`** |
| `__TEXT.__const` | `0xb78` | `0xb88` | **`+0x10`** |
| `__TEXT.__cstring` | `0xa3c` | `0xa4c` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x30e` | `0x31e` | **`+0x10`** |
| `__DATA.__objc_ivar` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 474
-  Symbols:   202
-  CStrings:  357
+  Functions: 482
+  Symbols:   216
+  CStrings:  376
Symbols:
+ _OBJC_CLASS_$_DAExclavesStatusCapture
+ _OBJC_METACLASS_$_DAExclavesStatusCapture
+ _dispatch_after
+ _dispatch_get_global_queue
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_wait
+ _dispatch_time
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_storeStrong
+ _swift_release_x10
- _swift_release_x9
CStrings:
+ "@\"NSDictionary\""
+ "@\"NSObject<OS_dispatch_group>\""
+ "@32@0:8Q16d24"
+ "DAExclavesStatusCapture"
+ "T@\"NSDictionary\",R,N"
+ "Td,N,V_displayPipeStatsDelay"
+ "_displayPipeStatsDelay"
+ "_indicatorStatusInnerForSensors:"
+ "captureGroup"
+ "d"
+ "d16@0:8"
+ "displayPipeStatsDelay"
+ "initWithSensors:"
+ "initWithSensors:displayPipeStatsDelay:"
+ "innerStatus"
+ "mutableCopy"
+ "setDisplayPipeStatsDelay:"
+ "status"
+ "v24@0:8d16"
```
