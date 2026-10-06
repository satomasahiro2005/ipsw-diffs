## modelcatalogdump

> `/usr/bin/modelcatalogdump`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18694` | `0x1ae1c` | **`+0x2788`** |
| `__TEXT.__eh_frame` | `0xef8` | `0x1060` | **`+0x168`** |
| `__TEXT.__auth_stubs` | `0x11e0` | `0x1250` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x8f8` | `0x930` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x528` | `0x558` | **`+0x30`** |
| `__TEXT.__cstring` | `0x922` | `0x942` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3d1` | `0x3e7` | **`+0x16`** |
| `__DATA.__data` | `0x378` | `0x388` | **`+0x10`** |
| `__TEXT.__const` | `0x5d4` | `0x5e4` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-302.1.0.2.0
+302.6.0.1.100

-  Functions: 520
+  Functions: 534

-  CStrings:  53
+  CStrings:  54
CStrings:
+ "  Evaluation Inputs & UDFs"
```
