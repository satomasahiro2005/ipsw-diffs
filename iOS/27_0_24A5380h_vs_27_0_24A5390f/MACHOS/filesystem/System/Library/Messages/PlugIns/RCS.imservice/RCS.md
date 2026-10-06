## RCS

> `/System/Library/Messages/PlugIns/RCS.imservice/RCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x6103` | `0x6123` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x5900` | `0x5920` | **`+0x20`** |
| `__TEXT.__text` | `0x1108f0` | `0x110908` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1938` | `0x1940` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  CStrings:  1685
+  CStrings:  1686
Functions:
~ sub_78b8c : 3688 -> 3712
CStrings:
+ "isFiltered"
+ "updateSpamModelMetadataWith:wasJunk:isJunk:"
- "setSpamModelMetadata:"
```
