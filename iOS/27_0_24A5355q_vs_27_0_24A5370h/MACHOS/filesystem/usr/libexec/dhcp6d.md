## dhcp6d

> `/usr/libexec/dhcp6d`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80e8` | `0x8154` | **`+0x6c`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-551.0.0.0.0
+553.0.0.0.0
Functions:
~ sub_100001e40 : 3020 -> 3028
~ sub_100002e54 -> sub_100002e5c : 800 -> 820
~ sub_100003174 -> sub_100003190 : 404 -> 412
~ sub_100003308 -> sub_10000332c : 432 -> 436
~ sub_100003b48 -> sub_100003b70 : 284 -> 280
~ sub_100003dbc -> sub_100003de0 : 184 -> 168
~ sub_100003fac -> sub_100003fc0 : 200 -> 196
~ sub_10000418c -> sub_10000419c : 1672 -> 1700
~ sub_100004a9c -> sub_100004ac8 : 864 -> 880
~ sub_100004ed4 -> sub_100004f10 : 172 -> 164
~ sub_100005244 -> sub_100005278 : 132 -> 140
~ sub_100005428 -> sub_100005464 : 1740 -> 1768
~ sub_100005af4 -> sub_100005b4c : 132 -> 136
~ sub_10000603c -> sub_100006098 : 408 -> 424
~ sub_10000624c -> sub_1000062b8 : 136 -> 140
~ sub_1000063b4 -> sub_100006424 : 196 -> 192
~ sub_100006574 -> sub_1000065e0 : 488 -> 484
~ sub_100007708 -> sub_100007770 : 900 -> 908
~ sub_100007e1c -> sub_100007e8c : 1920 -> 1916
```
