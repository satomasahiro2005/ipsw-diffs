## dockaccessoryd

> `/usr/libexec/dockaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1faf98` | `0x1fb2b4` | **`+0x31c`** |
| `__DATA_CONST.__got` | `0xca0` | `0xd30` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x14c7d` | `0x14cbd` | **`+0x40`** |
| `__TEXT.__const` | `0x5cb0` | `0x5c90` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x4b16` | `0x4af6` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x968` | `0x980` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4c08` | `0x4c20` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-411.0.0.0.0
+413.0.0.0.0

-  Functions: 6892
+  Functions: 6891

-  CStrings:  7022
+  CStrings:  7023
CStrings:
+ "set system tracking %s for %s [%d]"
```
