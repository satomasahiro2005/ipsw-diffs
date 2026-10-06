## ptpcamerad

> `/usr/libexec/ptpcamerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x1e50` | `0x1ed0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x45e5` | `0x460e` | **`+0x29`** |
| `__TEXT.__objc_methlist` | `0x171c` | `0x1734` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x13b0` | `0x13b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2114.0.0.0.0
+2116.0.0.0.0

-  CStrings:  1331
+  CStrings:  1333
CStrings:
+ "T@\"NSString\",?,R,C,N"
+ "mediaItemIdentifier"
```
