## SystemReport

> `/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d1b0` | `0x1d6dc` | **`+0x52c`** |
| `__TEXT.__objc_methname` | `0x346f` | `0x352f` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x4f80` | `0x5000` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3807` | `0x3874` | **`+0x6d`** |
| `__TEXT.__objc_stubs` | `0x42e0` | `0x4340` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0xc90` | `0xce0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x58a` | `0x5c5` | **`+0x3b`** |
| `__TEXT.__objc_methlist` | `0x1b04` | `0x1b3c` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x12a0` | `0x12c8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x658` | `0x680` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x650` | `0x658` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 610
-  Symbols:   322
-  CStrings:  1641
+  Functions: 615
+  Symbols:   327
+  CStrings:  1652
Symbols:
+ _IOObjectRetain
+ _IORegistryEntryFromPath
+ _IORegistryEntryGetName
+ _IORegistryEntryGetParentEntry
+ _strcmp
CStrings:
+ "@64@0:8@16@24@32@?40@48Q56"
+ "ComponentIndex"
+ "IODeviceTree:/product"
+ "^{__IOMobileFramebuffer=}16@0:8"
+ "coverglass-serial-number"
+ "coverglassSerialNumber"
+ "coverglassSerialNumberPropertyKey"
+ "getIORegistryClass:property:optionalKey:classValidator:ancestorNameContaining:ancestorDepth:"
+ "mobileFrameBuffer"
+ "raw-panel-serial-number"
+ "serialNumberPropertyKey"
```
