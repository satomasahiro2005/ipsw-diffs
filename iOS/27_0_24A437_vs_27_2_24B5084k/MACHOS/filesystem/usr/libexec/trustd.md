## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x6115` | `0x6139` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x5da0` | `0x5dc0` | **`+0x20`** |
| `__TEXT.__const` | `0xde40` | `0xde20` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x3de0` | `0x3de8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.2.3.0.0
+62460.40.49.502.1

-  CStrings:  2214
+  CStrings:  2215
CStrings:
+ "sec_count_all_with_access_groups_id"
```
