## absd

> `/usr/sbin/absd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22e9ac` | `0x243de8` | **`+0x1543c`** |
| `__TEXT.__const` | `0x3fcd0` | `0x3bf50` | **`-0x3d80`** |
| `__DATA_CONST.__const` | `0x135e8` | `0x13c50` | **`+0x668`** |
| `__DATA.__data` | `0xa18` | `0xce0` | **`+0x2c8`** |
| `__TEXT.__unwind_info` | `0x358` | `0x480` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x178` | `0xd0` | **`-0xa8`** |
| `__DATA.__common` | `0x14b4` | `0x14c0` | **`+0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`

### Other Changes

```diff

-  Functions: 239
+  Functions: 282
```
