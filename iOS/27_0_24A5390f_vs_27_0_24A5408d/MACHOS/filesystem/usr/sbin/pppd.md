## pppd

> `/usr/sbin/pppd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d444` | `0x2d3dc` | **`-0x68`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1029.0.0.0.1
+1031.0.0.0.4
Functions:
~ sub_10000adac : 1380 -> 1276
```
