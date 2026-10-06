## nvram

> `/usr/sbin/nvram`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2228` | `0x2214` | **`-0x14`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1068.0.0.0.0
+1070.0.0.0.0
Functions:
~ sub_100000730 : 3508 -> 3488
```
