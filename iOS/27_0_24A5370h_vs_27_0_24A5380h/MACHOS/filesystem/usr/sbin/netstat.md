## netstat

> `/usr/sbin/netstat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b058` | `0x1afe4` | **`-0x74`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x200` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`

### Other Changes

```diff

-754.0.0.0.0
+755.0.0.0.0
Functions:
~ _intpr_ri : 1860 -> 1852
~ _ipsec_hist : 256 -> 232
~ _knownname : 120 -> 104
~ _mbpr : 3280 -> 3212
~ _printb : 232 -> 236
~ _p_sockaddr : 872 -> 868
```
