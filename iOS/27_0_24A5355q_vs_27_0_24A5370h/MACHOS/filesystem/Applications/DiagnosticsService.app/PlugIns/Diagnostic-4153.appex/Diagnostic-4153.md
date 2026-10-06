## Diagnostic-4153

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4153.appex/Diagnostic-4153`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8090` | `0x8494` | **`+0x404`** |
| `__DATA.__objc_const` | `0x1118` | `0x1238` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x2bdf` | `0x2cf8` | **`+0x119`** |
| `__TEXT.__objc_stubs` | `0x23e0` | `0x2480` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x3a0` | `0x420` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xba8` | `0xc08` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0xbf7` | `0xc54` | **`+0x5d`** |
| `__DATA.__objc_data` | `0x1e0` | `0x230` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1e0` | `0x220` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xc08` | `0xc40` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1b8` | `0x1e0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x132` | `0x14a` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xd0` | `0xdc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__const` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3bf` | `0x3c1` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 195
-  Symbols:   162
-  CStrings:  691
+  Functions: 203
+  Symbols:   172
+  CStrings:  711
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
+ _objc_retain_x19
CStrings:
+ "@\"DAExclavesStatusCapture\""
+ "@\"NSObject<OS_dispatch_group>\""
+ "@32@0:8Q16d24"
+ "DAExclavesStatusCapture"
+ "T@\"DAExclavesStatusCapture\",&,N,V_exclavesCapture"
+ "T@\"NSDictionary\",R,N"
+ "Td,N,V_displayPipeStatsDelay"
+ "_displayPipeStatsDelay"
+ "_exclavesCapture"
+ "_indicatorStatusInnerForSensors:"
+ "captureGroup"
+ "d"
+ "d16@0:8"
+ "displayPipeStatsDelay"
+ "exclavesCapture"
+ "init"
+ "initWithSensors:"
+ "initWithSensors:displayPipeStatsDelay:"
+ "innerStatus"
+ "parseResultsWithExclavesStatus:"
+ "setDisplayPipeStatsDelay:"
+ "setExclavesCapture:"
+ "status"
+ "v24@0:8d16"
- "T@\"NSDictionary\",&,N,V_exclavesStatus"
- "_exclavesStatus"
- "parseResults"
- "setExclavesStatus:"
```
