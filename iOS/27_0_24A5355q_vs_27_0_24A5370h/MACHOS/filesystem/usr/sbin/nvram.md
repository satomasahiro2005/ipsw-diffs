## nvram

> `/usr/sbin/nvram`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0xd8` | `0xd0` | **`-0x8`** |
| `__TEXT.__text` | `0x2224` | `0x2228` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__const`

### Other Changes

```diff

-1066.0.0.0.0
+1068.0.0.0.0
Functions:
~ sub_100000730 : 3524 -> 3508
~ sub_100001584 -> sub_100001574 : 484 -> 492
~ sub_100001768 -> sub_100001760 : 708 -> 712
~ sub_100001a70 -> sub_100001a6c : 528 -> 524
~ sub_100001c80 -> sub_100001c78 : 1084 -> 1096
```
