## nlcd

> `/usr/libexec/nlcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5124` | `0x5144` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100000d0c : 144 -> 132
~ sub_100000d9c -> sub_100000d90 : 68 -> 72
~ sub_100000de0 -> sub_100000dd8 : 84 -> 92
~ sub_1000011d0 : 248 -> 256
~ sub_1000042b0 -> sub_1000042b8 : 744 -> 756
~ sub_1000046c4 -> sub_1000046d8 : 60 -> 64
~ sub_100004ac0 -> sub_100004ad8 : 152 -> 156
~ sub_10000567c -> sub_100005698 : 736 -> 740
```
