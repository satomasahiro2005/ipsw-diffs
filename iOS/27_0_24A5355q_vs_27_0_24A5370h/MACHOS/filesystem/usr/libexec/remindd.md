## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x802df0` | `0x805608` | **`+0x2818`** |
| `__TEXT.__const` | `0x28e48` | `0x28ef8` | **`+0xb0`** |
| `__DATA.__data` | `0x1efd0` | `0x1ef60` | **`-0x70`** |
| `__TEXT.__cstring` | `0x18bd7` | `0x18c17` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1f6c8` | `0x1f708` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x10008` | `0x10038` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x1b8a0` | `0x1b8c0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xc045` | `0xc065` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x13fa8` | `0x13fc4` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xa664` | `0xa67c` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x27cc1` | `0x27cd1` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x7b78` | `0x7b80` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x25840` | `0x25848` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0

-  Functions: 22445
+  Functions: 22450

-  CStrings:  11674
+  CStrings:  11677
Symbols:
+ _$s10Foundation13URLComponentsV8fragmentSSSgvs
+ _$sSo20CSCustomAttributeKeyC19ReminderKitInternalE12rem_objectIDABvgZ
+ _swift_release_x13
- _$s10Foundation13URLComponentsV22percentEncodedFragmentSSSgvs
- _$sSS19ReminderKitInternalE25urlFragmentRepresentationSSSgvg
- _objc_retain_x13
CStrings:
+ "attributeSet"
+ "deviceIndexVersion"
+ "remObjectIDByIdentifier"
+ "targetIndexVersion"
- "identifiers"
```
