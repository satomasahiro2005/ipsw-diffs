## iWorkFileFormat

> `/System/Library/PrivateFrameworks/iWorkXPC.framework/XPCServices/iWorkFileFormat.xpc/iWorkFileFormat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x163264` | `0x163584` | **`+0x320`** |
| `__TEXT.__objc_methname` | `0xe4e3` | `0xe53e` | **`+0x5b`** |
| `__TEXT.__cstring` | `0x1340d` | `0x1344e` | **`+0x41`** |
| `__TEXT.__objc_methtype` | `0x287b` | `0x28a5` | **`+0x2a`** |
| `__DATA.__objc_const` | `0xa960` | `0xa980` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xe9b0` | `0xe9d0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8d38` | `0x8d48` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3688` | `0x3690` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x639c` | `0x63a4` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x62c` | `0x630` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-30.0.0.0.0
+31.0.0.0.0

-  Functions: 8700
+  Functions: 8706

-  CStrings:  4862
+  CStrings:  4867
CStrings:
+ "-[NSSet(TSUAdditions) tsu_setByCompactMappingObjectsUsingBlock:]"
+ "@40@0:8@16q24^@32"
+ "@56@0:8@16@24@32q40^@48"
+ "_extendedAttributePreservationMode"
+ "initWithURL:package:fileCoordinatorDelegate:extendedAttributePreservationMode:error:"
+ "newPackageConverterWithURL:extendedAttributePreservationMode:error:"
+ "tsu_setByCompactMappingObjectsUsingBlock:"
- "initWithURL:package:fileCoordinatorDelegate:preserveExtendedAttributes:error:"
- "newPackageConverterWithURL:preserveExtendedAttributes:error:"
```
