## libedit.3.dylib

> `/usr/lib/libedit.3.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1591c` | `0x15830` | **`-0xec`** |
| `__AUTH.__data` | `—` | `0x10` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x18` | `0x8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x518` | `0x510` | **`-0x8`** |

### Other Changes

```text
Functions:
~ sub_2be632838 -> sub_2bf2b98d0 : 384 -> 368
~ sub_2be6336bc -> sub_2bf2ba744 : 228 -> 216
~ sub_2be634720 -> sub_2bf2bb79c : 180 -> 168
~ sub_2be63498c -> sub_2bf2bb9fc : 328 -> 320
~ sub_2be635b54 -> sub_2bf2bcbbc : 308 -> 292
~ _history_w : 2840 -> 2808
~ sub_2be639050 -> sub_2bf2c0088 : 256 -> 240
~ sub_2be639150 -> sub_2bf2c0178 : 112 -> 116
~ _history_expand : 3236 -> 3276
~ _history_tokenize : 696 -> 684
~ _rl_completion_matches : 444 -> 456
~ sub_2be63d634 -> sub_2bf2c4688 : 2996 -> 2968
~ sub_2be63e788 -> sub_2bf2c57c0 : 172 -> 140
~ sub_2be63f00c -> sub_2bf2c6024 : 208 -> 172
~ sub_2be63f2e0 -> sub_2bf2c62d4 : 304 -> 300
~ sub_2be63f974 -> sub_2bf2c6964 : 768 -> 748
~ sub_2be64136c -> sub_2bf2c8348 : 124 -> 136
~ sub_2be6413e8 -> sub_2bf2c83d0 : 104 -> 116
~ sub_2be64172c -> sub_2bf2c8720 : 396 -> 388
~ sub_2be64319c -> sub_2bf2ca188 : 1272 -> 1268
~ sub_2be6440ac -> sub_2bf2cb094 : 328 -> 356
~ sub_2be6445fc -> sub_2bf2cb600 : 500 -> 476
~ sub_2be644958 -> sub_2bf2cb944 : 220 -> 204
~ _history : 2820 -> 2772
```
