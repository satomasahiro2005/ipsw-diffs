## webinspectord

> `/usr/libexec/webinspectord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x934` | `0x8c4` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0xa8` | `0xb8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-7625.1.29.10.28
+7625.1.29.10.29
Functions:
~ sub_100001240 : 68 -> 56
~ sub_100001284 -> sub_100001278 : 68 -> 56
~ sub_100001470 -> sub_100001458 : 108 -> 96
~ sub_1000014dc -> sub_1000014b8 : 44 -> 32
~ sub_1000015b0 -> sub_100001580 : 120 -> 108
~ sub_1000016e0 -> sub_1000016a4 : 448 -> 428
~ sub_1000018a0 -> sub_100001850 : 472 -> 440
```
