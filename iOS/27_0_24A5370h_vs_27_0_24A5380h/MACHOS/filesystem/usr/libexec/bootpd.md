## bootpd

> `/usr/libexec/bootpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10fa4` | `0x10f8c` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-553.0.0.0.0
+554.0.0.0.0
Functions:
~ sub_1000037b0 : 724 -> 732
~ sub_100004c28 -> sub_100004c30 : 1524 -> 1508
~ sub_10000521c -> sub_100005214 : 308 -> 272
~ sub_100005e28 -> sub_100005dfc : 7544 -> 7548
~ sub_100007e68 -> sub_100007e40 : 128 -> 132
~ sub_10000ad3c -> sub_10000ad18 : 700 -> 708
~ sub_10000cc78 -> sub_10000cc5c : 424 -> 428
~ sub_10000d164 -> sub_10000d14c : 332 -> 360
~ sub_10000d59c -> sub_10000d5a0 : 52 -> 40
~ _SubnetGetOptionPtrAndLength : 96 -> 88
~ _SubnetListCreateWithArray : 1788 -> 1772
~ sub_10000fd28 -> sub_10000fd08 : 164 -> 168
~ sub_100010660 -> sub_100010644 : 652 -> 656
```
