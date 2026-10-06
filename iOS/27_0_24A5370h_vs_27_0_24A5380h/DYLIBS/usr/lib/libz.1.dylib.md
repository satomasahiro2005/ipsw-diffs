## libz.1.dylib

> `/usr/lib/libz.1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb95c` | `0xb790` | **`-0x1cc`** |
| `__TEXT.__unwind_info` | `0x218` | `0x210` | **`-0x8`** |

### Other Changes

```diff

-104.0.0.0.0
+105.0.0.0.0
Functions:
~ sub_2bff2a9b8 -> sub_2c0fcb9b8 : 472 -> 484
~ _inflate : 6480 -> 6000
~ _adler32_z : 320 -> 300
~ _adler32 : 8 -> 16
~ sub_2bff2e9c0 -> sub_2c0fcf7e0 : 1164 -> 1180
~ _deflateInit_ -> sub_2c0fd1f74 : 28 -> 248
~ sub_2bff31160 -> _gzclose_w : 8 -> 220
~ _deflateBound -> _deflateInit_ : 292 -> 28
~ _gzclose_w -> sub_2c0fd2164 : 220 -> 8
~ sub_2bff31368 -> _deflateBound : 248 -> 292
~ sub_2bff32410 -> sub_2c0fd3240 : 980 -> 984
```
