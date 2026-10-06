## InputUI

> `/Applications/InputUI.app/InputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x6214` | `0x6254` | **`+0x40`** |
| `__DATA.__objc_const` | `0x5650` | `0x5670` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x22ac` | `0x22c4` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1738` | `0x1748` | **`+0x10`** |
| `__TEXT.__text` | `0xbffc` | `0xbff4` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x3d8` | `0x3e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-109.8.0.0.0
+109.10.0.0.0

-  CStrings:  1398
+  CStrings:  1400
CStrings:
+ "prefersCompactNumberPadLayout"
+ "setPrefersCompactNumberPadLayout:"
```
