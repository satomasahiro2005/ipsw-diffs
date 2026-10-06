## syslogd

> `/usr/sbin/syslogd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1356c` | `0x1352c` | **`-0x40`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100001588 : 312 -> 288
~ sub_100004120 -> sub_100004108 : 2172 -> 2188
~ sub_100006a00 -> sub_1000069f8 : 1560 -> 1532
~ sub_10000a0f0 -> sub_10000a0cc : 244 -> 240
~ sub_10000a41c -> sub_10000a3f4 : 5832 -> 5868
~ sub_1000101d0 -> sub_1000101cc : 376 -> 360
~ sub_1000103c8 -> sub_1000103b4 : 784 -> 780
~ sub_100010a98 -> sub_100010a80 : 304 -> 288
~ sub_100010f94 -> sub_100010f6c : 1784 -> 1764
~ sub_100012c00 -> sub_100012bc4 : 168 -> 172
~ sub_100012ef4 -> sub_100012ebc : 420 -> 412
```
