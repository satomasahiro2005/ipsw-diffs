## codecctl

> `/usr/bin/codecctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82d4` | `0x8330` | **`+0x5c`** |
| `__TEXT.__const` | `0x84` | `0x7c` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x600` | `0x608` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-600.75.1.0.0
+600.79.0.0.0
Functions:
~ sub_1000025b0 : 28 -> 40
~ sub_100002b78 -> sub_100002b84 : 720 -> 716
~ sub_100003e84 -> sub_100003e8c : 64 -> 84
~ sub_1000047a8 -> sub_1000047c4 : 60 -> 80
~ sub_100004874 -> sub_1000048a4 : 80 -> 92
~ sub_100005214 -> sub_100005250 : 300 -> 292
~ sub_100005e20 -> sub_100005e54 : 248 -> 260
~ sub_1000065f8 -> sub_100006638 : 696 -> 700
~ sub_10000759c -> sub_1000075e0 : 28 -> 40
~ sub_100007aec -> sub_100007b3c : 28 -> 40
```
