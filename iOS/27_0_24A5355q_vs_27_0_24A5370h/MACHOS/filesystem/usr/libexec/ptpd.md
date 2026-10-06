## ptpd

> `/usr/libexec/ptpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22524` | `0x224f0` | **`-0x34`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2112.0.0.0.0
+2113.0.0.0.0
Functions:
~ sub_10000e4d4 : 572 -> 568
~ sub_100010c34 -> sub_100010c30 : 312 -> 308
~ sub_100010e4c -> sub_100010e44 : 320 -> 316
~ sub_1000115c4 -> sub_1000115b8 : 2052 -> 2048
~ sub_1000135a0 -> sub_100013590 : 1340 -> 1336
~ sub_100013eb4 -> sub_100013ea0 : 352 -> 348
~ sub_100014014 -> sub_100013ffc : 1700 -> 1696
~ sub_1000146b8 -> sub_10001469c : 328 -> 324
~ sub_100014800 -> sub_1000147e0 : 1272 -> 1268
~ sub_100016d48 -> sub_100016d24 : 764 -> 760
~ sub_10001f538 -> sub_10001f510 : 548 -> 544
~ sub_10001f75c -> sub_10001f730 : 3120 -> 3116
~ sub_1000208e0 -> sub_1000208b0 : 2980 -> 2976
```
