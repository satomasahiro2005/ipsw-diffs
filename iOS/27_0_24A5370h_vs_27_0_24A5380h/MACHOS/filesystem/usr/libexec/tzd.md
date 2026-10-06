## tzd

> `/usr/libexec/tzd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15cc4` | `0x15c58` | **`-0x6c`** |
| `__DATA_CONST.__got` | `0x298` | `0x278` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0xf60` | `0xf50` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x7b8` | `0x7b0` | **`-0x8`** |
| `__TEXT.__const` | `0x8b8` | `0x8b0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x47c` | `0x476` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 425
-  Symbols:   408
+  Functions: 424
+  Symbols:   403
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _$sytN
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
```
