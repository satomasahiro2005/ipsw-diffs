## zprint

> `/usr/bin/zprint`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27d0` | `0x2744` | **`-0x8c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1066.0.0.0.0
+1068.0.0.0.0
Functions:
~ sub_100000828 : 3880 -> 3808
~ sub_1000018e0 -> sub_100001898 : 1800 -> 1748
~ sub_100001fe8 -> sub_100001f6c : 2232 -> 2216
```
