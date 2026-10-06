## ifconfig

> `/sbin/ifconfig`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc94` | `0xbc20` | **`-0x74`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-754.0.0.0.0
+755.0.0.0.0
Functions:
~ _bond_status : 772 -> 740
~ _main : 8308 -> 8300
~ _printb : 228 -> 232
~ _setifsubfamily : 236 -> 256
~ _netem_parse_args : 1356 -> 1296
~ _setmedia : 376 -> 368
~ _domediaopt : 492 -> 484
~ _get_subtype_desc : 112 -> 96
~ _bridge_status : 3296 -> 3288
```
