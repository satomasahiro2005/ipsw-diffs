## dmd

> `/usr/libexec/dmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81624` | `0x812dc` | **`-0x348`** |
| `__TEXT.__objc_stubs` | `0xe940` | `0xe960` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1182a` | `0x11846` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x4190` | `0x4198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-258.0.0.0.0
+259.0.0.0.0

-  CStrings:  4518
+  CStrings:  4519
CStrings:
+ "valueRestrictionForFeature:"
```
