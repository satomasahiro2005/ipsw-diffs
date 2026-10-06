## sysmond

> `/usr/libexec/sysmond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x370c` | `0x371c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x138` | `0x148` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```text
Functions:
~ sub_1000017ec : 536 -> 524
~ sub_100001af0 -> sub_100001ae4 : 132 -> 148
~ sub_1000022ac -> sub_1000022b0 : 380 -> 372
~ sub_100002514 -> sub_100002510 : 132 -> 148
~ sub_1000029e0 -> sub_1000029ec : 132 -> 128
~ sub_100002c2c -> sub_100002c34 : 92 -> 108
~ sub_100002da8 -> sub_100002dc0 : 164 -> 148
~ sub_100003248 -> sub_100003250 : 108 -> 124
~ sub_100003560 -> sub_100003578 : 292 -> 284
```
