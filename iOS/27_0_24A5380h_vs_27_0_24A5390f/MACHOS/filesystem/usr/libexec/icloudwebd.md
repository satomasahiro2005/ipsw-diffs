## icloudwebd

> `/usr/libexec/icloudwebd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6971c` | `0x698f4` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0xe37` | `0xe67` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x1f10` | `0x1f20` | **`+0x10`** |
| `__TEXT.__const` | `0x7160` | `0x7150` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xf90` | `0xf98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-71.1.0.0.0
+71.3.0.0.0

-  Symbols:   839
-  CStrings:  721
+  Symbols:   840
+  CStrings:  722
Symbols:
+ _$sSo13os_log_type_ta0A0E5faultABvgZ
+ _exit
- _swift_errorInMain
CStrings:
+ "Failed to initialize SkyBridge daemon: %@"
```
