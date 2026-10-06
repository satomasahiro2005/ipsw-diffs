## centaurid

> `/usr/libexec/centaurid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30ba8` | `0x30c80` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x5d3e` | `0x5d62` | **`+0x24`** |
| `__TEXT.__cstring` | `0x19b91` | `0x19ba3` | **`+0x12`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-124.0.0.0.1
+127.0.0.0.0

-  Functions: 628
+  Functions: 629

-  CStrings:  3509
+  CStrings:  3511
CStrings:
+ "%{public}@::%{public}@: version: %s"
+ "AppleCentauri-127"
```
