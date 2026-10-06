## guidedbrowsingd

> `/usr/libexec/guidedbrowsingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13c0` | `0x1204` | **`-0x1bc`** |
| `__TEXT.__unwind_info` | `0xe8` | `0x100` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x138` | `0x140` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7625.1.29.10.28
+7625.1.29.10.29
Functions:
~ sub_100001450 : 816 -> 756
~ sub_100001780 -> sub_100001744 : 80 -> 68
~ sub_1000018f0 -> sub_1000018a8 : 184 -> 172
~ sub_1000019a8 -> sub_100001954 : 292 -> 240
~ sub_100001b04 -> sub_100001a7c : 344 -> 292
~ sub_100001c5c -> sub_100001ba0 : 544 -> 532
~ sub_100001e7c -> sub_100001db4 : 264 -> 212
~ sub_100001f84 -> sub_100001e88 : 308 -> 296
~ sub_1000020b8 -> sub_100001fb0 : 244 -> 192
~ sub_1000021ac -> sub_100002070 : 172 -> 160
~ sub_100002258 -> sub_100002110 : 264 -> 212
~ sub_100002470 -> sub_1000022f4 : 208 -> 176
~ sub_100002540 -> sub_1000023a4 : 164 -> 132
```
