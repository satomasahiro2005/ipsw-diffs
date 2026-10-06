## swift-inspect

> `/usr/bin/swift-inspect`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95d1c` | `0x95b9c` | **`-0x180`** |
| `__TEXT.__eh_frame` | `0x32a0` | `0x32d8` | **`+0x38`** |
| `__DATA.__data` | `0x1e10` | `0x1e28` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1b00` | `0x1b10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xd88` | `0xd90` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xf10` | `0xf08` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1af0` | `0x1af8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2108` | `0x2110` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6.4.0.27.101
+6.4.0.31.4

-  Functions: 3130
-  Symbols:   863
+  Functions: 3135
+  Symbols:   865
Symbols:
+ _$sSS8UTF8ViewV13_foreignCountSiyF
+ _$sSiSzsMc
```
