## jetpackassetd

> `/System/Library/PrivateFrameworks/JetCore.framework/Support/jetpackassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3b54` | `0xb4478` | **`+0x924`** |
| `__TEXT.__eh_frame` | `0x84b0` | `0x8568` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x5ed4` | `0x5f34` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2f58` | `0x2fa8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2940` | `0x2970` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x444` | `0x468` | **`+0x24`** |
| `__TEXT.__const` | `0x3de8` | `0x3e08` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2ea0` | `0x2e90` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x8e0` | `0x8ec` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x1758` | `0x1750` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x244` | `0x24c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x52c` | `0x534` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-10.0.43.0.0
+10.0.47.0.0

-  Functions: 2153
-  Symbols:   1155
-  CStrings:  720
+  Functions: 2164
+  Symbols:   1154
+  CStrings:  722
Symbols:
- _swift_retain_x22
CStrings:
+ "Failed to pre-warm AMS at startup: "
+ "Pre-warming AMS at startup via bag fetch"
```
