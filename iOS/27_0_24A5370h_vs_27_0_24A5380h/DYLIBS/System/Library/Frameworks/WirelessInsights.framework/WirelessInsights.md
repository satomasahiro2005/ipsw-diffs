## WirelessInsights

> `/System/Library/Frameworks/WirelessInsights.framework/WirelessInsights`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x855c8` | `0x85480` | **`-0x148`** |
| `__AUTH.__objc_data` | `0x48` | `0x188` | **`+0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x468` | `0x328` | **`-0x140`** |
| `__DATA.__bss` | `0xfe70` | `0xfe60` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x9580` | `0x9590` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x43f0` | `0x43f8` | **`+0x8`** |

### Other Changes

```diff

-341.0.0.0.0
+344.0.0.0.0
Functions:
~ sub_247843e6c -> sub_24c3bce6c : 420 -> 408
~ __ZN3wis12MetricBuffer17_deleteOldMetricsEv : 392 -> 368
~ sub_24784a5dc -> sub_24c3c35b8 : 168 -> 160
~ sub_24784a684 -> sub_24c3c3658 : 608 -> 588
~ sub_24784afb4 -> sub_24c3c3f74 : 484 -> 476
~ sub_24784b57c -> sub_24c3c4534 : 144 -> 128
~ sub_24784b60c -> sub_24c3c45b4 : 192 -> 184
~ sub_24784e90c -> sub_24c3c78ac : 144 -> 124
~ sub_2478505a0 -> sub_24c3c952c : 96 -> 84
~ sub_24785357c -> sub_24c3cc4fc : 96 -> 84
~ sub_247856ad0 -> sub_24c3cfa44 : 116 -> 100
~ __ZN3wis20ServerConnectionInfo28handleNotificationTimer_syncEj : 844 -> 840
~ sub_247867b9c -> sub_24c3e0afc : 172 -> 152
~ sub_247867c48 -> sub_24c3e0b94 : 524 -> 500
~ sub_247867e54 -> sub_24c3e0d88 : 132 -> 124
~ sub_24786805c -> sub_24c3e0f88 : 268 -> 248
~ sub_24786b080 -> sub_24c3e3f98 : 220 -> 192
~ sub_24786b15c -> sub_24c3e4058 : 236 -> 216
~ sub_24786b400 -> sub_24c3e42e8 : 460 -> 456
~ sub_24786b5cc -> sub_24c3e44b0 : 684 -> 640
```
