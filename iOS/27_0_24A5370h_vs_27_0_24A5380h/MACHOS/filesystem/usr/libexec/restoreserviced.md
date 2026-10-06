## restoreserviced

> `/usr/libexec/restoreserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x180` | `0x190` | **`+0x10`** |
| `__TEXT.__text` | `0x142dc` | `0x142e8` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-46.0.0.0.0
+48.0.0.0.0
Functions:
~ sub_10000c130 : 2816 -> 2824
~ sub_10000ed64 -> sub_10000ed6c : 272 -> 276
```
