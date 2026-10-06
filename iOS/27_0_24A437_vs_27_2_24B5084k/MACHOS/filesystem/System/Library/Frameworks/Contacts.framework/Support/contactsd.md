## contactsd

> `/System/Library/Frameworks/Contacts.framework/Support/contactsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x5aad` | `0x5b3d` | **`+0x90`** |
| `__TEXT.__objc_methtype` | `0x12e7` | `0x133f` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1c6c` | `0x1c7c` | **`+0x10`** |
| `__TEXT.__text` | `0x2fe34` | `0x2fe44` | **`+0x10`** |
| `__DATA.__objc_const` | `0x3130` | `0x3138` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x15f8` | `0x1600` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
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

-3844.100.1.0.0
+3846.200.41.0.0

-  CStrings:  1386
+  CStrings:  1389
Functions:
~ sub_100006a64 : 240 -> 256
~ sub_10000bc18 -> sub_10000bc28 : 8 -> 12
~ sub_10000bc30 -> sub_10000bc44 : 12 -> 8
CStrings:
+ "@\"<CNCancelable>\"48@0:8d16@?<v@?>24d32Q40"
+ "@48@0:8d16@?24d32Q40"
+ "afterDelay:performBlock:delayTolerance:qualityOfService:"
```
