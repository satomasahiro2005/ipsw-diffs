## mount_nfs

> `/sbin/mount_nfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6960` | `0x697c` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-356.0.0.0.0
+356.0.3.0.0
Functions:
~ sub_1000009c8 : 144 -> 152
~ sub_100000a58 -> sub_100000a60 : 3196 -> 3188
~ sub_100003728 : 216 -> 212
~ sub_100003ca8 -> sub_100003ca4 : 1028 -> 1048
~ sub_1000050ec -> sub_1000050fc : 4896 -> 4900
~ sub_100006518 -> sub_10000652c : 268 -> 260
~ sub_100006624 -> sub_100006630 : 172 -> 184
~ sub_1000068a0 -> sub_1000068b8 : 340 -> 344
```
