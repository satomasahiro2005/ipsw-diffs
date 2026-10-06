## aidearlyboot

> `/usr/libexec/aidearlyboot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa304` | `0xa2e4` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x1820` | `0x1830` | **`+0x10`** |
| `__TEXT.__const` | `0xd660` | `0xd668` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10100.34.0.0.0
+10100.38.1.0.0
Functions:
~ sub_1000017dc : 552 -> 548
~ sub_1000026f8 -> sub_1000026f4 : 1040 -> 1036
~ sub_100002b70 -> sub_100002b68 : 988 -> 976
~ sub_100002f7c -> sub_100002f68 : 1212 -> 1204
~ sub_100003578 -> sub_10000355c : 760 -> 756
~ sub_100005fc8 -> sub_100005fa8 : 720 -> 724
~ sub_100006b70 -> sub_100006b54 : 432 -> 436
~ sub_100006d20 -> sub_100006d08 : 592 -> 588
~ sub_1000084b4 -> sub_100008498 : 1040 -> 1036
```
