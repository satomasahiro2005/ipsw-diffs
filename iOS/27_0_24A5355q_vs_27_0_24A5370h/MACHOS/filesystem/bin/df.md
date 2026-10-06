## df

> `/bin/df`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x175c` | `0x1788` | **`+0x2c`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-486.0.0.0.0
+487.0.0.0.0
Functions:
~ sub_100000698 : 3116 -> 3156
~ sub_100001340 -> sub_100001368 : 248 -> 244
~ sub_100001438 -> sub_10000145c : 120 -> 140
~ sub_1000014b0 -> sub_1000014e8 : 260 -> 248
```
