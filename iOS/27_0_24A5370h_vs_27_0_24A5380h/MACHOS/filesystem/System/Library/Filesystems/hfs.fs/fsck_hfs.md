## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/fsck_hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34be8` | `0x34ba8` | **`-0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-748.0.0.0.0
+749.0.0.0.0
Functions:
~ sub_100000ec4 : 572 -> 548
~ sub_100001100 -> sub_1000010e8 : 632 -> 616
~ sub_10000686c -> sub_100006844 : 472 -> 464
~ sub_100007cd4 -> sub_100007ca4 : 516 -> 532
~ sub_10000aad0 -> sub_10000aab0 : 3852 -> 3896
~ sub_100010970 -> sub_10001097c : 1148 -> 1160
~ sub_1000160d0 -> sub_1000160e8 : 588 -> 564
~ sub_100021bec : 320 -> 316
~ sub_10002a6e0 -> sub_10002a6dc : 480 -> 492
~ sub_10002cea4 -> sub_10002ceac : 96 -> 80
~ sub_10002cf04 -> sub_10002cefc : 676 -> 660
~ sub_10002d200 -> sub_10002d1e8 : 2120 -> 2116
~ sub_10002da48 -> sub_10002da2c : 3076 -> 3068
~ sub_1000317c0 -> sub_10003179c : 3816 -> 3812
~ sub_100032cfc -> sub_100032cd4 : 336 -> 324
~ sub_100033ff0 -> sub_100033fbc : 2228 -> 2220
~ sub_100034998 -> sub_10003495c : 700 -> 696
```
