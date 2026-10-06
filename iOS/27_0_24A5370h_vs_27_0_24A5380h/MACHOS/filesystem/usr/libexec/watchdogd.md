## watchdogd

> `/usr/libexec/watchdogd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd28` | `0xdd1c` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-334.0.1.0.0
+334.0.3.0.0
Functions:
~ sub_100005204 : 316 -> 304
```
