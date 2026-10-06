## hangreporter

> `/usr/libexec/hangreporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25e20` | `0x260d0` | **`+0x2b0`** |
| `__DATA_CONST.__cfstring` | `0x52a0` | `0x5320` | **`+0x80`** |
| `__TEXT.__cstring` | `0x42bf` | `0x431b` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x1640` | `0x1680` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x5c78` | `0x5c82` | **`+0xa`** |
| `__TEXT.__objc_methtype` | `0x8ef` | `0x8f8` | **`+0x9`** |
| `__TEXT.__unwind_info` | `0x608` | `0x600` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-421.0.0.0.0
+424.0.0.0.0

-  CStrings:  2132
+  CStrings:  2136
Functions:
~ sub_100006da4 : 240 -> 296
~ sub_100006ee4 -> sub_100006f1c : 296 -> 424
~ sub_100007534 -> sub_1000075ec : 484 -> 664
~ sub_1000086ac -> sub_100008818 : 496 -> 548
~ sub_10000889c -> sub_100008a3c : 300 -> 308
~ sub_100008a48 -> sub_100008bf0 : 776 -> 736
~ sub_100011b34 -> sub_100011cb4 : 180 -> 216
~ sub_100013890 -> sub_100013a34 : 168 -> 172
~ sub_100014dac -> sub_100014f54 : 2148 -> 2144
~ sub_100015d50 -> sub_100015ef4 : 9156 -> 9220
~ sub_10001d764 -> sub_10001d948 : 212 -> 416
CStrings:
+ "@56@0:8@16Q24Q32Q40Q48"
+ "end_matu"
+ "hangtracer.hang_end"
+ "hangtracer.hang_start"
+ "hangtracer.sample_end"
+ "hangtracer.sample_start"
+ "intervalsByClippingIntervals:toHangStart:hangEnd:sampleStart:sampleEnd:"
+ "jsonStringForIntervals:"
+ "start_matu"
- "@32@0:8@16Q24"
- "end_ms"
- "intervalsByClippingIntervals:toWindowStart:end:"
- "jsonStringForIntervals:hangStartMATU:"
- "start_ms"
```
