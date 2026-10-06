## ckksctl

> `/usr/sbin/ckksctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cec` | `0x5d84` | **`+0x98`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0
Functions:
~ sub_100000cc0 : 312 -> 320
~ sub_100000e6c -> sub_100000e74 : 1320 -> 1488
~ sub_100002030 -> sub_1000020e0 : 412 -> 408
~ sub_100002318 -> sub_1000023c4 : 6816 -> 6808
~ sub_100004648 -> sub_1000046ec : 968 -> 964
~ sub_100004edc -> sub_100004f7c : 1068 -> 1060
~ sub_1000057c4 -> sub_10000585c : 2448 -> 2460
~ sub_100006154 -> sub_1000061f8 : 368 -> 364
~ sub_1000062c4 -> sub_100006364 : 344 -> 340
~ sub_10000641c -> sub_1000064b8 : 864 -> 860
```
