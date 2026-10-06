## symptomsd-darwin

> `/usr/libexec/symptomsd-darwin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xe0` | `0xd8` | **`-0x8`** |
| `__TEXT.__text` | `0x3594` | `0x358c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2357.0.0.0.2
+2374.0.0.0.0
Functions:
~ sub_100003de0 : 64 -> 60
~ sub_100004198 -> sub_100004194 : 156 -> 152
```
