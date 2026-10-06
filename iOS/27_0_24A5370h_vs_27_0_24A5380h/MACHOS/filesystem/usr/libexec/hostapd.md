## hostapd

> `/usr/libexec/hostapd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29f14` | `0x29f10` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__eh_frame`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-425.1.0.0.0
+425.2.0.0.0
Functions:
~ sub_100000de0 : 836 -> 816
~ sub_1000027d8 -> sub_1000027c4 : 792 -> 836
~ sub_10000cd14 -> sub_10000cd2c : 1032 -> 1076
~ sub_10000d74c -> sub_10000d790 : 316 -> 312
~ sub_10001032c -> sub_10001036c : 656 -> 668
~ sub_100015d60 -> sub_100015dac : 180 -> 172
~ sub_100015e14 -> sub_100015e58 : 228 -> 220
~ sub_10001761c -> sub_100017658 : 7392 -> 7380
~ sub_1000192fc -> sub_10001932c : 628 -> 596
~ sub_100019570 -> sub_100019580 : 456 -> 448
~ sub_100019738 -> sub_100019740 : 456 -> 448
~ sub_100026184 : 284 -> 292
~ sub_10002976c -> sub_100029774 : 232 -> 220
```
