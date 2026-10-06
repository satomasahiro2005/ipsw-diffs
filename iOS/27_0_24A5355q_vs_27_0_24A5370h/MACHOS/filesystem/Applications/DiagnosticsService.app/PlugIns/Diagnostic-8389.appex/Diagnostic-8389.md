## Diagnostic-8389

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8389.appex/Diagnostic-8389`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ecf4` | `0x1dc9c` | **`-0x1058`** |
| `__DATA.__objc_const` | `0xad0` | `0xbf0` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0xa40` | `0xb00` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0xed0` | `0xf70` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x155d` | `0x15fd` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x574` | `0x5d4` | **`+0x60`** |
| `__DATA.__objc_data` | `0x798` | `0x7e8` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x770` | `0x7c0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x81b` | `0x86b` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x4b0` | `0x4e8` | **`+0x38`** |
| `__TEXT.__const` | `0x36a0` | `0x36d0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2100` | `0x2128` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x1d4` | `0x1f4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8d0` | `0x8e8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xbc7` | `0xbd9` | **`+0x12`** |
| `__TEXT.__cstring` | `0x11ad` | `0x11bd` | **`+0x10`** |
| `__DATA.__objc_ivar` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x682` | `0x683` | **`+0x1`** |

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
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 850
-  Symbols:   184
-  CStrings:  418
+  Functions: 857
+  Symbols:   196
+  CStrings:  438
Symbols:
+ _OBJC_CLASS_$_DAExclavesStatusCapture
+ _OBJC_METACLASS_$_DAExclavesStatusCapture
+ _dispatch_after
+ _dispatch_get_global_queue
+ _dispatch_group_wait
+ _dispatch_time
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_retain_x25
+ _objc_storeStrong
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
+ "exclavesCapture"
+ "initWithSensors:"
+ "initWithSensors:displayPipeStatsDelay:"
+ "innerStatus"
+ "mutableCopy"
+ "setDisplayPipeStatsDelay:"
+ "status"
+ "v24@0:8d16"
```
