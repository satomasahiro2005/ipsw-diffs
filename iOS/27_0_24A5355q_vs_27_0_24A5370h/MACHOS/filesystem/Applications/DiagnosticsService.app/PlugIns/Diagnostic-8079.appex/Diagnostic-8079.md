## Diagnostic-8079

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8079.appex/Diagnostic-8079`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x855c` | `0x8944` | **`+0x3e8`** |
| `__DATA.__objc_const` | `0x1818` | `0x1938` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x2812` | `0x291f` | **`+0x10d`** |
| `__TEXT.__objc_stubs` | `0x2340` | `0x2400` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x4c0` | `0x550` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0xb34` | `0xb94` | **`+0x60`** |
| `__DATA.__objc_data` | `0x500` | `0x550` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x2b8` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x327` | `0x36f` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0xa00` | `0xa38` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x238` | `0x260` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x188` | `0x1a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x210` | `0x228` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x108` | `0x114` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0xab4` | `0xabc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 232
-  Symbols:   174
-  CStrings:  675
+  Functions: 240
+  Symbols:   185
+  CStrings:  692
Symbols:
+ _OBJC_CLASS_$_DAExclavesStatusCapture
+ _OBJC_METACLASS_$_DAExclavesStatusCapture
+ _dispatch_get_global_queue
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_wait
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
CStrings:
+ "@\"DAExclavesStatusCapture\""
+ "@\"NSObject<OS_dispatch_group>\""
+ "@32@0:8Q16d24"
+ "Beginning Exclaves status capture"
+ "DAExclavesStatusCapture"
+ "T@\"DAExclavesStatusCapture\",&,N,V_exclavesCapture"
+ "T@\"NSDictionary\",R,N"
+ "Td,N,V_displayPipeStatsDelay"
+ "_displayPipeStatsDelay"
+ "_exclavesCapture"
+ "_indicatorStatusInnerForSensors:"
+ "captureGroup"
+ "displayPipeStatsDelay"
+ "exclavesCapture"
+ "initWithSensors:"
+ "initWithSensors:displayPipeStatsDelay:"
+ "innerStatus"
+ "mutableCopy"
+ "setDisplayPipeStatsDelay:"
+ "setExclavesCapture:"
+ "status"
- "Capturing exclaves status"
- "T@\"NSDictionary\",&,N,V_exclavesStatus"
- "_exclavesStatus"
- "setExclavesStatus:"
```
