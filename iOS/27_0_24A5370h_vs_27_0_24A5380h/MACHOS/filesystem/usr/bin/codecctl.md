## codecctl

> `/usr/bin/codecctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8330` | `0x82cc` | **`-0x64`** |
| `__TEXT.__unwind_info` | `0x608` | `0x600` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-600.79.0.0.0
+600.80.0.0.0
Functions:
~ sub_1000025b0 : 40 -> 28
~ sub_100003e8c -> sub_100003e80 : 84 -> 64
~ sub_100004124 -> sub_100004104 : 36 -> 32
~ sub_1000047c4 -> sub_1000047a0 : 80 -> 60
~ sub_1000048a4 -> sub_10000486c : 92 -> 80
~ sub_100005374 -> sub_100005330 : 292 -> 284
~ sub_1000075e0 -> sub_100007594 : 40 -> 28
~ sub_100007b3c -> sub_100007ae4 : 40 -> 28
```
