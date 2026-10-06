## Diagnostic-8246

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8246.appex/Diagnostic-8246`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4568` | `0x4950` | **`+0x3e8`** |
| `__DATA.__objc_const` | `0x9d8` | `0xaf8` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x1688` | `0x1795` | **`+0x10d`** |
| `__TEXT.__objc_stubs` | `0x1560` | `0x1620` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x3d0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x634` | `0x694` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x3be` | `0x41b` | **`+0x5d`** |
| `__DATA.__objc_data` | `0x140` | `0x190` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1f8` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x6f8` | `0x730` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x110` | `0x138` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x128` | `0x148` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0xad` | `0xc5` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x70` | `0x7c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1c6` | `0x1c8` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 116
-  Symbols:   133
-  CStrings:  407
+  Functions: 124
+  Symbols:   143
+  CStrings:  427
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
+ "initWithSensors:"
+ "initWithSensors:displayPipeStatsDelay:"
+ "innerStatus"
+ "mutableCopy"
+ "setDisplayPipeStatsDelay:"
+ "setExclavesCapture:"
+ "status"
+ "v24@0:8d16"
- "T@\"NSDictionary\",&,N,V_exclavesStatus"
- "_exclavesStatus"
- "setExclavesStatus:"
```
