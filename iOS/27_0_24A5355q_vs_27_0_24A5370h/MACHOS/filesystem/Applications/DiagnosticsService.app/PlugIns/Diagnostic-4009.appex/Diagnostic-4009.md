## Diagnostic-4009

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4009.appex/Diagnostic-4009`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7114` | `0x75ec` | **`+0x4d8`** |
| `__TEXT.__objc_methname` | `0x192b` | `0x1adf` | **`+0x1b4`** |
| `__DATA.__objc_const` | `0x1280` | `0x13d0` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x1720` | `0x1840` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0xce4` | `0xd64` | **`+0x80`** |
| `__DATA.__objc_data` | `0x3c0` | `0x410` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x710` | `0x760` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x72f` | `0x777` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x210` | `0x238` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x9c0` | `0x9e0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x690` | `0x6b0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x290` | `0x2b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xaf9` | `0xb18` | **`+0x1f`** |
| `__TEXT.__objc_classname` | `0x13b` | `0x153` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x358` | `0x368` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__const` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 235
-  Symbols:   203
-  CStrings:  545
+  Functions: 246
+  Symbols:   207
+  CStrings:  567
Symbols:
+ _OBJC_CLASS_$_DAExclavesStatusCapture
+ _OBJC_METACLASS_$_DAExclavesStatusCapture
+ _dispatch_after
+ _dispatch_get_global_queue
CStrings:
+ "@\"DAExclavesStatusCapture\""
+ "@\"NSObject<OS_dispatch_group>\""
+ "@32@0:8Q16d24"
+ "DAExclavesStatusCapture"
+ "T@\"DAExclavesStatusCapture\",&,N,V_exclavesCapture"
+ "T@\"NSDictionary\",R,N"
+ "T@\"NSNumber\",N,V_displayPipeStatsCaptureDelay"
+ "Td,N,V_displayPipeStatsDelay"
+ "_displayPipeStatsCaptureDelay"
+ "_displayPipeStatsDelay"
+ "_exclavesCapture"
+ "_indicatorStatusInnerForSensors:"
+ "beginExclavesCaptureIfNeeded"
+ "captureGroup"
+ "displayPipeStatsCaptureDelay"
+ "displayPipeStatsDelay"
+ "exclavesCapture"
+ "initWithSensors:"
+ "initWithSensors:displayPipeStatsDelay:"
+ "innerStatus"
+ "mutableCopy"
+ "setDisplayPipeStatsCaptureDelay:"
+ "setDisplayPipeStatsDelay:"
+ "setExclavesCapture:"
+ "status"
- "T@\"NSDictionary\",&,N,V_exclavesStatus"
- "_exclavesStatus"
- "setExclavesStatus:"
```
