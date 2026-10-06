## dockaccessoryd

> `/usr/libexec/dockaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa7ac` | `0x1fafb8` | **`+0x80c`** |
| `__TEXT.__unwind_info` | `0x4c20` | `0x4c00` | **`-0x20`** |
| `__DATA.__data` | `0x7050` | `0x7040` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x39b0` | `0x39c0` | **`+0x10`** |
| `__TEXT.__const` | `0x5ca0` | `0x5cb0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x29c0` | `0x29b2` | **`-0xe`** |
| `__DATA_CONST.__auth_got` | `0x1ce8` | `0x1cf0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x970` | `0x968` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-410.1.0.0.0
+411.0.0.0.0

-  Functions: 6893
+  Functions: 6892
Symbols:
+ _objc_retain_x11
- _$ss15CollectionOfOneVMn
```
