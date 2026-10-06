## restorecameraispd

> `/usr/libexec/restorecameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3259` | `0x32fc` | **`+0xa3`** |
| `__TEXT.__text` | `0x1cf84` | `0x1d010` | **`+0x8c`** |
| `__DATA_CONST.__cfstring` | `0x15c0` | `0x15e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x80b0` | `0x80b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x570` | `0x568` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 421
+  Functions: 420

-  CStrings:  630
+  CStrings:  634
CStrings:
+ "/usr/local/share/firmware/isp/dcs_v6x_isp_fw.bin"
+ "FrontCameraRenoModuleSerialNumString"
+ "com.apple.isp.frontrenocamerapower"
+ "com.apple.isp.frontrenocamerasensorconfig"
```
