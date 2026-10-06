## ioreg

> `/usr/sbin/ioreg`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e98` | `0x3e54` | **`-0x44`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100000cac : 612 -> 596
~ sub_100001064 -> sub_100001054 : 476 -> 472
~ sub_100001a58 -> sub_100001a44 : 676 -> 656
~ sub_100002568 -> sub_100002540 : 3848 -> 3832
~ sub_100003544 -> sub_10000350c : 1012 -> 1004
~ sub_100003b6c -> sub_100003b2c : 700 -> 696
```
