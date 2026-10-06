## SMS

> `/System/Library/Messages/PlugIns/SMS.imservice/SMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10aa4` | `0x10b08` | **`+0x64`** |
| `__TEXT.__objc_stubs` | `0x2ac0` | `0x2b00` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x48c7` | `0x48ea` | **`+0x23`** |
| `__DATA.__objc_selrefs` | `0x1028` | `0x1038` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  CStrings:  1022
+  CStrings:  1024
Functions:
~ sub_b544 : 1048 -> 1148
CStrings:
+ "set"
+ "setLastUPIVisibilityCheckDate:"
```
