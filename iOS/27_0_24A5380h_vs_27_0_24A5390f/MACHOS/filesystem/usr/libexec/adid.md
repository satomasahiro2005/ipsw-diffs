## adid

> `/usr/libexec/adid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24ac34` | `0x256cd0` | **`+0xc09c`** |
| `__DATA_CONST.__const` | `0x14420` | `0x14b58` | **`+0x738`** |
| `__DATA.__data` | `0xfd0` | `0x10d0` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x180` | `0x1d8` | **`+0x58`** |
| `__DATA.__common` | `0x198` | `0x190` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-21.1.0.0.0
+21.3.0.0.0

-  Functions: 91
+  Functions: 106
```
