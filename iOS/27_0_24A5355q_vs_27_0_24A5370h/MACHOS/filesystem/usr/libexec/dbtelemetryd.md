## dbtelemetryd

> `/usr/libexec/dbtelemetryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5eb0` | `0x61b0` | **`+0x300`** |
| `__TEXT.__auth_stubs` | `0x9a0` | `0xa10` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x16c` | `0x1cc` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x238` | `0x288` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x18d` | `0x1dd` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x4d8` | `0x510` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x14` | `0x3c` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__const` | `0x2e2` | `0x2f2` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1d8` | `0x1e7` | **`+0xf`** |
| `__DATA.__data` | `0x1f8` | `0x200` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-5.0.0.0.0
+6.0.0.0.0

-  Functions: 112
-  Symbols:   256
-  CStrings:  45
+  Functions: 115
+  Symbols:   263
+  CStrings:  47
Symbols:
+ _objc_release_x28
+ _objc_retain_x28
+ _swift_release_n
+ _swift_release_x27
+ _swift_release_x28
+ _swift_retain_x27
+ _swift_retain_x28
CStrings:
+ "Expiration already requested before processing started; stopping extractor"
+ "stopProcessing"
```
