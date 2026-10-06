## df

> `/bin/df`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x4a` | `0x52` | **`+0x8`** |
| `__TEXT.__text` | `0x1788` | `0x178c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-487.0.0.0.0
+487.0.1.0.0
Functions:
~ sub_100000698 : 3156 -> 3152
~ sub_10000145c -> sub_100001458 : 140 -> 148
```
