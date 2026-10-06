## powerdatad

> `/usr/libexec/powerdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7578` | `0x7588` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x108` | `0x110` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2041.0.0.502.1
+2043.0.13.502.1
Functions:
~ sub_100005804 : 128 -> 136
~ sub_100005884 -> sub_10000588c : 108 -> 116
```
