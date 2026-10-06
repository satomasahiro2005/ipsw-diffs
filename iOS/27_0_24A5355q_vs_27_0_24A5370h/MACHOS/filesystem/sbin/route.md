## route

> `/sbin/route`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c8c` | `0x3cc4` | **`+0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _print_rtmsg : 472 -> 468
~ _routename : 864 -> 880
~ _netname : 760 -> 768
~ _prefixlen : 244 -> 240
~ _rtmsg : 1032 -> 1056
~ _mask_addr : 268 -> 284
```
