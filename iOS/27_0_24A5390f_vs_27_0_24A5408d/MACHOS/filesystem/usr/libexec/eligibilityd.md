## eligibilityd

> `/usr/libexec/eligibilityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_arraydata` | `0xc520` | `0xc690` | **`+0x170`** |
| `__DATA_CONST.__objc_dictobj` | `0xb2c0` | `0xb400` | **`+0x140`** |
| `__DATA_CONST.__objc_arrayobj` | `0x2fa0` | `0x3030` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x5600` | `0x5620` | **`+0x20`** |
| `__TEXT.__text` | `0x43a2c` | `0x43a14` | **`-0x18`** |
| `__TEXT.__cstring` | `0x708f` | `0x709a` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-446.0.2.0.0
+446.2.1.0.0

-  CStrings:  2019
+  CStrings:  2020
Functions:
~ sub_1000325d0 : 1368 -> 1356
~ sub_100039738 -> sub_10003972c : 796 -> 784
CStrings:
+ "00:03:56"
+ "446.2.1"
+ "Aug  4 2026"
+ "BlockChina"
- "00:57:27"
- "446.0.2"
- "Jul 10 2026"
```
