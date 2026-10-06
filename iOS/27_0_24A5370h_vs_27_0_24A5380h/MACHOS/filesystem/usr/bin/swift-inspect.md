## swift-inspect

> `/usr/bin/swift-inspect`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95cc4` | `0x95d1c` | **`+0x58`** |
| `__DATA.__data` | `0x1e28` | `0x1e10` | **`-0x18`** |
| `__TEXT.__const` | `0xa2f2` | `0xa2e2` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x20c3` | `0x20b3` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2100` | `0x2108` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6.4.0.23.102
+6.4.0.25.5

-  Functions: 3133
-  Symbols:   864
+  Functions: 3130
+  Symbols:   863
Symbols:
- _swift_runtimeSupportsNoncopyableTypes
```
