## Diagnostic-9016

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9016.appex/Diagnostic-9016`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c4` | `0xfa0` | **`-0x824`** |
| `__TEXT.__objc_stubs` | `0x5a0` | `0x360` | **`-0x240`** |
| `__TEXT.__objc_methname` | `0x677` | `0x564` | **`-0x113`** |
| `__DATA_CONST.__cfstring` | `0x5a0` | `0x4a0` | **`-0x100`** |
| `__TEXT.__cstring` | `0x4c2` | `0x41c` | **`-0xa6`** |
| `__TEXT.__auth_stubs` | `0x290` | `0x200` | **`-0x90`** |
| `__DATA.__objc_selrefs` | `0x280` | `0x210` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0x158` | `0x110` | **`-0x48`** |
| `__DATA_CONST.__got` | `0xa0` | `0x78` | **`-0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Symbols:   79
-  CStrings:  192
+  Symbols:   65
+  CStrings:  170
Symbols:
- _AMSupportLogSetHandler
- _OBJC_CLASS_$_CRDeviceMap
- _OBJC_CLASS_$_CRFDRUtils
- _OBJC_CLASS_$_CRUtils
- _OBJC_CLASS_$_NSNumber
- __logHandler
- _objc_release_x25
- _objc_release_x26
- _objc_release_x27
- _objc_release_x28
- _objc_retain
- _objc_retain_x22
- _objc_retain_x23
- _objc_retain_x27
Functions:
~ sub_1000010b0 : 2496 -> 412
CStrings:
- "Missing required partSPC"
- "Unknown error updating YonkersIR"
- "Unknown error updating YonkersIR1"
- "Unknown error updating YonkersIR2"
- "addObject:"
- "allObjects"
- "code"
- "componentsJoinedByString:"
- "containsObject:"
- "failedSPC"
- "firstObject"
- "getInnermostNSError:"
- "intersectSet:"
- "isDataClassWithTypeInfoSupported:"
- "localizedDescription"
- "mutableCopy"
- "numberWithInteger:"
- "sealingMapCopyMultiInstanceForClassWithTypeInfo:error:"
- "supportSecureRCAM"
- "ycrt-innf"
- "ycrt-outf"
- "ycrt-rcam"
```
