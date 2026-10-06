## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b2d8` | `0x4b448` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x374a` | `0x380a` | **`+0xc0`** |
| `__DATA_CONST.__objc_intobj` | `0xa38` | `0xac8` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x1680` | `0x16e0` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2ecd` | `0x2edd` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 1862
+  Functions: 1864

-  CStrings:  2390
+  CStrings:  2396
CStrings:
+ "BPCC"
+ "Failed to write btp0 for shelf life mode. Aborting shutdown."
+ "Failed to write btp1 for shelf life mode. Aborting shutdown."
+ "Multipack system detected. Using btp0/btp1 for shelf life mode."
+ "btp0"
+ "btp1"
```
