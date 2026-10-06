## frauddefensed

> `/usr/libexec/frauddefensed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2dc4` | `0xd3130` | **`+0x36c`** |
| `__TEXT.__eh_frame` | `0xa520` | `0xa578` | **`+0x58`** |
| `__TEXT.__cstring` | `0x9ecb` | `0x9f1b` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x1662` | `0x16a2` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1200` | `0x1240` | **`+0x40`** |
| `__TEXT.__const` | `0x79cc` | `0x79ec` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x35c0` | `0x35d8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1d30` | `0x1d44` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x5b0` | `0x5c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x640` | `0x648` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-94.0.0.0.0
+95.0.0.0.0

-  Functions: 3369
-  Symbols:   928
-  CStrings:  1045
+  Functions: 3371
+  Symbols:   929
+  CStrings:  1049
Symbols:
+ _OBJC_CLASS_$_CKContainerID
CStrings:
+ "Fetched remote entities. { database="
+ "ckSandboxEnvironment"
+ "initWithContainerID:"
+ "initWithContainerIdentifier:environment:"
```
