## fsck_exfat

> `/System/Library/Filesystems/exfat.fs/fsck_exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb58` | `0xcc30` | **`+0xd8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-560.0.0.0.0
+561.0.0.0.0
Functions:
~ sub_100000b98 : 168 -> 200
~ sub_100001124 -> sub_100001144 : 760 -> 768
~ sub_100001738 -> sub_100001760 : 1732 -> 1736
~ sub_100001f5c -> sub_100001f88 : 688 -> 696
~ sub_1000022e4 -> sub_100002318 : 964 -> 972
~ sub_100002a34 -> sub_100002a70 : 368 -> 384
~ sub_100002d48 -> sub_100002d94 : 360 -> 368
~ sub_100002f38 -> sub_100002f8c : 160 -> 168
~ sub_100003084 -> sub_1000030e0 : 332 -> 340
~ sub_100003d6c -> sub_100003dd0 : 476 -> 484
~ sub_1000040a4 -> sub_100004110 : 180 -> 188
~ sub_1000042b0 -> sub_100004324 : 2364 -> 2336
~ sub_100005258 -> sub_1000052b0 : 760 -> 768
~ sub_1000055f8 -> sub_100005658 : 752 -> 760
~ sub_100006398 -> sub_100006400 : 2288 -> 2296
~ sub_100006ce4 -> sub_100006d54 : 244 -> 252
~ sub_1000071b8 -> sub_100007230 : 1808 -> 1816
~ sub_10000798c -> sub_100007a0c : 756 -> 764
~ sub_100007c80 -> sub_100007d08 : 732 -> 740
~ sub_100008130 -> sub_1000081c0 : 668 -> 676
~ sub_1000083cc -> sub_100008464 : 484 -> 492
~ sub_100008c58 -> sub_100008cf8 : 2792 -> 2800
~ sub_10000a4cc -> sub_10000a574 : 5280 -> 5308
~ sub_10000c768 -> sub_10000c82c : 632 -> 648
~ sub_10000cf70 -> sub_10000d044 : 80 -> 84
```
