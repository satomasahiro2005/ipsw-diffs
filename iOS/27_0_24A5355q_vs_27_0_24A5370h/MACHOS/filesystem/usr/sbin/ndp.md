## ndp

> `/usr/sbin/ndp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c5c` | `0x3c40` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _main : 6420 -> 6404
~ _rtrlist : 672 -> 668
~ _set : 892 -> 884
~ _read_cga_parameters : 556 -> 560
~ _rtilist : 824 -> 820
```
