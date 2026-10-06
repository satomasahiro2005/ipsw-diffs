## ps

> `/bin/ps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4428` | `0x4488` | **`+0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100000be0 : 1092 -> 1096
~ sub_100002778 -> sub_10000277c : 252 -> 248
~ sub_100002960 : 4216 -> 4340
~ sub_1000040a4 -> sub_100004120 : 452 -> 440
~ sub_100004568 -> sub_1000045d8 : 924 -> 908
```
