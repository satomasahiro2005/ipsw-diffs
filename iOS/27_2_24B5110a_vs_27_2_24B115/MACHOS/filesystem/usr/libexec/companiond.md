## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x25b0` | `0x25a8` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__const`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-524.11.6.0.0
+524.11.10.0.0
Functions:
~ sub_10002b5fc : 20 -> 108
~ sub_10002b6e8 -> sub_10002b740 : 108 -> 132
~ sub_10002b754 -> sub_10002b7c4 : 132 -> 20
```
