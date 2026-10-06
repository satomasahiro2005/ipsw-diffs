## audiomxd

> `/usr/libexec/audiomxd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43dc` | `0x4498` | **`+0xbc`** |
| `__TEXT.__cstring` | `0x4c0` | `0x4ca` | **`+0xa`** |
| `__TEXT.__gcc_except_tab` | `0x374` | `0x378` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1638.209.1.0.0
+1638.211.0.0.0

-  CStrings:  92
+  CStrings:  93
Functions:
~ sub_1000042f8 : 1520 -> 1708
CStrings:
+ "ftruncate"
```
