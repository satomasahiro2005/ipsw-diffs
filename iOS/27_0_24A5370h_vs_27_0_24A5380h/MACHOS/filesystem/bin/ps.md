## ps

> `/bin/ps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4488` | `0x444c` | **`-0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100000be0 : 1096 -> 1068
~ sub_100002960 -> sub_100002944 : 4340 -> 4308
```
