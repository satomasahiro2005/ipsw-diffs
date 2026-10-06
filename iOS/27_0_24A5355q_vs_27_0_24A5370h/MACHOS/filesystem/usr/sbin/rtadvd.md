## rtadvd

> `/usr/sbin/rtadvd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a98` | `0x7ad8` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-551.0.0.0.0
+553.0.0.0.0
Functions:
~ sub_100000970 : 132 -> 144
~ sub_1000009f4 -> sub_100000a00 : 468 -> 416
~ sub_100000bc8 -> sub_100000ba0 : 232 -> 224
~ sub_100000f54 -> sub_100000f24 : 5712 -> 5792
~ sub_1000025f4 -> sub_100002614 : 640 -> 652
~ sub_100002874 -> sub_1000028a0 : 192 -> 196
~ sub_100002934 -> sub_100002964 : 1812 -> 1832
~ sub_1000034d4 -> sub_100003518 : 1768 -> 1760
~ sub_100004058 -> sub_100004094 : 580 -> 588
~ sub_1000045e0 -> sub_100004624 : 624 -> 648
~ sub_100004850 -> sub_1000048ac : 2236 -> 2224
~ sub_100005604 -> sub_100005654 : 6384 -> 6380
~ sub_10000745c -> sub_1000074a8 : 540 -> 528
```
