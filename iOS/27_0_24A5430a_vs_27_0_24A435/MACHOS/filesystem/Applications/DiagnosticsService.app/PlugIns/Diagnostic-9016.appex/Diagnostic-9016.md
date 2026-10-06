## Diagnostic-9016

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9016.appex/Diagnostic-9016`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc7c` | `0x17c4` | **`+0xb48`** |
| `__TEXT.__objc_stubs` | `0x340` | `0x5a0` | **`+0x260`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x5a0` | **`+0x240`** |
| `__TEXT.__cstring` | `0x36b` | `0x4c2` | **`+0x157`** |
| `__TEXT.__objc_methname` | `0x52f` | `0x677` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0x91` | `0x17f` | **`+0xee`** |
| `__TEXT.__auth_stubs` | `0x1e0` | `0x290` | **`+0xb0`** |
| `__DATA.__objc_selrefs` | `0x1f8` | `0x280` | **`+0x88`** |
| `__DATA_CONST.__auth_got` | `0x100` | `0x158` | **`+0x58`** |
| `__DATA_CONST.__objc_arraydata` | `0xa8` | `0xe0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x70` | `0xa0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x23c` | `0x264` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x253` | `0x25f` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-  Functions: 20
-  Symbols:   62
-  CStrings:  150
+  Functions: 28
+  Symbols:   79
+  CStrings:  192
Symbols:
+ _AMSupportLogSetHandler
+ _OBJC_CLASS_$_CRDeviceMap
+ _OBJC_CLASS_$_CRFDRUtils
+ _OBJC_CLASS_$_CRUtils
+ _OBJC_CLASS_$_NSNumber
+ ___kCFBooleanTrue
+ __logHandler
+ _objc_opt_new
+ _objc_release_x25
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain
+ _objc_retainAutorelease
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x27
CStrings:
+ "B24@0:8^@16"
+ "IPHONE AUX BATTERY"
+ "IPHONE COMP FCAM"
+ "IPHONE COMP TOUCHID"
+ "IPHONE IO BOARD"
+ "IPHONE MAIN DISPLAY"
+ "IPHONE MAIN FCAM"
+ "IPHONE VOL BUTTON"
+ "Missing required partSPC"
+ "Start to update YonkersIR firmware ..."
+ "Start to update YonkersIR1 firmware ..."
+ "Start to update YonkersIR2 firmware ..."
+ "Unknown error updating YonkersIR"
+ "Unknown error updating YonkersIR1"
+ "Unknown error updating YonkersIR2"
+ "Update YonkersIR firmware successfully"
+ "Update YonkersIR1 firmware successfully"
+ "Update YonkersIR2 firmware successfully"
+ "addObject:"
+ "allObjects"
+ "code"
+ "componentsJoinedByString:"
+ "containsObject:"
+ "failedSPC"
+ "firstObject"
+ "getInnermostNSError:"
+ "intersectSet:"
+ "isDataClassWithTypeInfoSupported:"
+ "localizedDescription"
+ "mutableCopy"
+ "numberWithInteger:"
+ "sealingMapCopyMultiInstanceForClassWithTypeInfo:error:"
+ "supportSecureRCAM"
+ "updateYonkersIR"
+ "updateYonkersIR1"
+ "updateYonkersIR1:"
+ "updateYonkersIR2"
+ "updateYonkersIR2:"
+ "updateYonkersIR:"
+ "ycrt-innf"
+ "ycrt-outf"
+ "ycrt-rcam"
```
