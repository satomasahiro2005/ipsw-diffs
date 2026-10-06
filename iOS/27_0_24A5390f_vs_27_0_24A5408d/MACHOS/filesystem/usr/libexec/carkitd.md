## carkitd

> `/usr/libexec/carkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94cfc` | `0x94ef4` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x114d1` | `0x11581` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x11600` | `0x11620` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x18a74` | `0x18a84` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x50a0` | `0x50a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2200` | `0x2208` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-797.0.0.0.0
+799.2.0.0.0

-  CStrings:  6817
+  CStrings:  6822
CStrings:
+ "closedCaptionsEnabled"
+ "device supports theme assets for this asset ID"
+ "device supports theme assets: %@"
+ "not connected but updated available styles: %@"
+ "updated available styles while connected: %@"
```
