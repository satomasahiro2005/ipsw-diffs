## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4de348` | `0x4de474` | **`+0x12c`** |
| `__TEXT.__eh_frame` | `0x261f4` | `0x26244` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x283c` | `0x2880` | **`+0x44`** |
| `__TEXT.__objc_methname` | `0x20449` | `0x20479` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1d790` | `0x1d770` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x18a60` | `0x18a80` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdeee` | `0xdede` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x7160` | `0x7168` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1fe8` | `0x1ff0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-482.30.6.14.20
+482.30.6.14.19

-  Functions: 16287
+  Functions: 16288
CStrings:
+ "-[FMDSharedConfigurationManager getRepairStateWithContext:timeout:completion:]_block_invoke_2"
+ "initWithDevices:"
+ "initWithSerialNumbers:thisDeviceSerialNumber:"
- "-[FMDSharedConfigurationManager getRepairStateWithContext:timeout:completion:]_block_invoke_3"
- "addDevice:"
- "v24@?0@8^B16"
```
