## fmflocatord

> `/usr/libexec/fmflocatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38624` | `0x38948` | **`+0x324`** |
| `__TEXT.__gcc_except_tab` | `0x7cc` | `0x840` | **`+0x74`** |
| `__TEXT.__objc_methname` | `0x836f` | `0x83df` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x2071` | `0x20c1` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x70a0` | `0x70e0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x8690` | `0x86c0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x383c` | `0x3854` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf18` | `0xf30` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2258` | `0x2268` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x12db` | `0x12eb` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2a4` | `0x2a8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-103.30.6.7.1
+103.30.6.7.10

-  Functions: 1557
+  Functions: 1561

-  CStrings:  2606
+  CStrings:  2611
CStrings:
+ "@\"NSData\""
+ "T@\"NSData\",&,N,V_inProgressRegisterDigest"
+ "_inProgressRegisterDigest"
+ "inProgressRegisterDigest"
+ "setInProgressRegisterDigest:"
```
