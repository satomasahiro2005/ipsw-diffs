## pppd

> `/usr/sbin/pppd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d3dc` | `0x2d3e8` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_10000dec4 : 1204 -> 1200
~ _parse_args : 324 -> 336
~ sub_1000276e0 -> sub_1000276e8 : 2572 -> 2576
```
