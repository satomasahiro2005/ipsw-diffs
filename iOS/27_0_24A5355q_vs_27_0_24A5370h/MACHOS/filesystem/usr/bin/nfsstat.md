## nfsstat

> `/usr/bin/nfsstat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8208` | `0x8220` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-356.0.0.0.0
+356.0.3.0.0
Functions:
~ sub_10000120c : 200 -> 196
~ sub_100001300 -> sub_1000012fc : 128 -> 136
~ sub_100001aac -> sub_100001ab0 : 192 -> 200
~ sub_100001bc0 -> sub_100001bcc : 328 -> 324
~ sub_100001ff4 -> sub_100001ffc : 188 -> 192
~ sub_100002408 -> sub_100002414 : 416 -> 440
~ sub_1000046dc -> sub_100004700 : 188 -> 220
~ sub_100004850 -> sub_100004894 : 580 -> 564
~ sub_100004a94 -> sub_100004ac8 : 6792 -> 6772
~ sub_100006668 -> sub_100006688 : 4400 -> 4392
~ sub_100007798 -> sub_1000077b0 : 2296 -> 2288
~ sub_100008240 -> sub_100008250 : 412 -> 416
~ sub_10000881c -> sub_100008830 : 164 -> 168
```
