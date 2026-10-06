## remoted

> `/usr/libexec/remoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d534` | `0x3d5f4` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x84b3` | `0x8502` | **`+0x4f`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xdd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-245.0.4.0.0
+245.0.6.0.0

-  Functions: 1375
+  Functions: 1376

-  CStrings:  1775
+  CStrings:  1776
CStrings:
+ "get_local_device_description denied: missing entitlement (client=\"%{public}s\")"
```
