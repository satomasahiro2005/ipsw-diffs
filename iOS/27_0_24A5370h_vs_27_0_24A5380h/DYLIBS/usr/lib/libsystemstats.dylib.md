## libsystemstats.dylib

> `/usr/lib/libsystemstats.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77ec` | `0x77f4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x240` | `0x238` | **`-0x8`** |

### Other Changes

```diff

-515.0.0.0.0
+515.0.1.0.0
Functions:
~ sub_2bfe6fd1c -> _systemstats_get_microstackshot_cycle_interval_override : 412 -> 352
~ _systemstats_get_microstackshot_cycle_interval_xlog_tasking -> sub_2c0f10e7c : 352 -> 412
~ sub_2bfe7014c -> sub_2c0f1114c : 276 -> 220
~ sub_2bfe70260 -> sub_2c0f11228 : 572 -> 276
~ sub_2bfe7049c -> sub_2c0f1133c : 372 -> 572
~ sub_2bfe70610 -> sub_2c0f11578 : 404 -> 372
~ __systemstats_get_file_stats -> sub_2c0f116ec : 4 -> 404
~ sub_2bfe707a8 -> __systemstats_get_file_stats : 220 -> 4
~ sub_2bfe7092c -> sub_2c0f1192c : 48 -> 56
```
