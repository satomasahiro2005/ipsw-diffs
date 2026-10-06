## logd_helper

> `/usr/libexec/logd_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d18` | `0x5d9c` | **`+0x84`** |
| `__TEXT.__const` | `0x130` | `0x140` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1952.0.0.0.0
+1958.0.0.0.1
Functions:
~ sub_1000010a0 : 304 -> 300
~ sub_10000144c -> sub_100001448 : 2012 -> 2040
~ sub_100001c28 -> sub_100001c40 : 716 -> 748
~ sub_100001ef4 -> sub_100001f2c : 1448 -> 1472
~ sub_10000249c -> sub_1000024ec : 708 -> 724
~ sub_100002760 -> sub_1000027c0 : 144 -> 164
~ sub_1000028a0 -> sub_100002914 : 1084 -> 1068
~ sub_100003684 -> sub_1000036e8 : 1664 -> 1652
~ sub_100004130 -> sub_100004188 : 1344 -> 1348
~ sub_100004870 -> sub_1000048cc : 192 -> 200
~ sub_10000501c -> sub_100005080 : 1128 -> 1124
~ sub_1000054cc -> sub_10000552c : 1636 -> 1668
~ sub_10000600c -> sub_10000608c : 144 -> 148
```
